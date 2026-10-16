# Datos para reproducir el análisis

El docente del módulo FDL proporcionó el enlace a [`credit_score.csv`](https://github.com/delveeducation/datasets/blob/main/credit_score.csv). La copia revisada contiene 96.696 filas, 28 columnas y 12.087 identificadores de cliente, cada uno con ocho meses. No se ha confirmado la licencia de redistribución ni el proceso de creación de las etiquetas. Por eso, el CSV no forma parte de este repositorio.

SHA-256 de la copia usada para las cifras publicadas: `55A368BFD390560614ADB0727864D5004110A75E0115F12F3B313AB955FD9BEA`.

Para reproducir los resultados, descarga el archivo desde la fuente enlazada y guárdalo localmente como `data/credit_score.csv`. La carpeta `data/` está excluida de Git.

## Variables usadas

`age`, `annual_income`, `monthly_inhand_salary`, `total_emi_per_month`, `num_bank_accounts`, `num_credit_card`, `interest_rate`, `num_of_loan`, `num_of_delayed_payment`, `outstanding_debt`, `credit_utilization_ratio`, `amount_invested_monthly` y `monthly_balance` se utilizan como predictores numéricos. `credit_score` es la etiqueta de tres clases codificadas como 0, 1 y 2. `customer_id` solo sirve para separar clientes entre entrenamiento y prueba.

El archivo también incluye `name` y `ssn`, entre otras columnas que el análisis no utiliza. No se conoce el significado documentado de los códigos de `credit_score` ni se puede determinar con este archivo si representan personas reales o datos generados.

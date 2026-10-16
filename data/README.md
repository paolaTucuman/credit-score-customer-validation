# Datos para reproducir el análisis

El docente del módulo FDL proporcionó [`credit_score.csv`](credit_score.csv) para el trabajo final. El archivo también está disponible en la [fuente del curso](https://github.com/delveeducation/datasets/blob/main/credit_score.csv). Contiene 96.696 filas, 28 columnas y 12.087 identificadores de cliente, cada uno con ocho meses. El proceso de creación de las etiquetas no está documentado.

SHA-256 del archivo incluido y usado para las cifras publicadas: `55A368BFD390560614ADB0727864D5004110A75E0115F12F3B313AB955FD9BEA`.

El notebook lee `data/credit_score.csv` desde la raíz del repositorio. No hace falta descargar otra copia para reproducir los resultados.

## Variables usadas

`age`, `annual_income`, `monthly_inhand_salary`, `total_emi_per_month`, `num_bank_accounts`, `num_credit_card`, `interest_rate`, `num_of_loan`, `num_of_delayed_payment`, `outstanding_debt`, `credit_utilization_ratio`, `amount_invested_monthly` y `monthly_balance` se utilizan como predictores numéricos. `credit_score` es la etiqueta de tres clases codificadas como 0, 1 y 2. `customer_id` solo sirve para separar clientes entre entrenamiento y prueba.

El archivo también incluye `name` y `ssn`, entre otras columnas que el análisis no utiliza. Es un conjunto de práctica; no se conoce el significado documentado de los códigos de `credit_score`.

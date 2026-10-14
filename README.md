Regional Ecological and Socio-Economic Data Analysis in R 🌍

This repository contains the solution for a data analysis assignment using R. The project focuses on processing, cleaning, and merging official statistical data for the regions of Kazakhstan, specifically looking at water purification infrastructure and population demographics.

📋 Project Overview

The assignment consists of two main parts, performed entirely using R without external table editors:

Data Cleaning & Deviation Calculation: Loading a dataset on water purification facilities, filtering out metadata and summary rows, and calculating the deviation of each region's facilities from the national mean. Outputs a strict 3-column table.

Data Merging & Feature Engineering: Loading a second dataset (population), cleaning complex numerical strings (handling spacing in digits), joining both datasets using inner_join, and calculating a new socio-economic metric: "Population load per water purification facility". Outputs a strict 4-column table.

🛠️ Technologies & Libraries

Language: R

Libraries: tidyverse (data manipulation via piping %>%, filter, mutate, inner_join), readxl (reading raw data), writexl (exporting results).

📂 Repository Structure

Seminar2_Mamadayev.Rmd — The main R Markdown script containing all the logic.

Seminar2_Mamadayev.nb.html — The generated HTML report.

Data_Water.xls & population.xls — Raw input datasets from the Bureau of National Statistics.

result_Mamadayev.xlsx & result_Part2_Mamadayev.xlsx — Processed output data.

Анализ региональных экологических и социально-экономических показателей в R 🌍

В этом репозитории представлено решение практического задания по анализу данных с использованием языка R. Проект посвящен обработке, очистке и объединению официальных статистических данных по регионам Казахстана (инфраструктура водоочистки и демография).

📋 Описание проекта

Работа состоит из двух основных частей, выполненных исключительно средствами R без использования внешних табличных редакторов:

Очистка данных и расчет отклонения: Загрузка датасета по водоочистным сооружениям, отсеивание метаданных и итоговых строк, а также расчет отклонения показателя каждого региона от среднего значения по стране. Результат экспортируется в таблицу из 3 столбцов.

Объединение данных (Join) и расчет нового показателя: Загрузка второго датасета (население), сложная очистка числовых данных от лишних пробелов с помощью регулярных выражений, объединение двух таблиц через inner_join и расчет нового социально-экологического показателя — "Демографическая нагрузка на 1 водоочистное сооружение". Результат экспортируется в таблицу из 4 столбцов.

🛠️ Инструменты и библиотеки

Язык: R

Библиотеки: tidyverse (конвейерная обработка %>%, filter, mutate, inner_join), readxl (чтение исходников), writexl (экспорт результатов).

📂 Структура репозитория

Seminar2_Mamadayev.Rmd — Основной скрипт R Markdown со всем кодом.

Seminar2_Mamadayev.nb.html — Сгенерированный HTML-отчет для удобного просмотра.

Data_Water.xls и population.xls — Исходные данные Бюро национальной статистики РК.

result_Mamadayev.xlsx и result_Part2_Mamadayev.xlsx — Итоговые файлы с рассчитанными 

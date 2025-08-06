# Анализ данных для текста о дефиците акушерок — от ...
# English version below

Этот репозиторий содержит данные, код и результаты, которые подтверждают части текста о нехватке акушерок и акушеров-гинекологов [TKTKTKTK](https://friendly2.me/support/glasnaya/), опубликованного **ДД/ММ/ГГГГ**. Пожалуйста, прочитайте сам текст, содержащий важный контекст и подробности, прежде чем продолжить.

## Данные

В данном анализе используются данные вакансий с платформы "Работы в России" и из Росстата.

Данные получены из следующих источников:

- [Платформа "Работа в России"](https://trudvsem.ru)
- [Единая межведомственная информационно–статистическая система (ЕМИСС)](https://fedstat.ru)


Итоговый файл [`MAIN dataset with personnel.xlsx`](https://github.com/yanina-sorokina/glasnaya/blob/main/MAIN%20dataset%20with%20personnel.xlsx) содержит, помимо прочего, следующие столбцы, имеющие отношение к анализу:

- `id` - уникальный код вакансии
- `region_name` - название региона, в котором опубликована вакансия
- `code_profession` - код профессии по ОКПДТР (Общероссийский классификатор профессий рабочих, должностей служащих и тарифных разрядов)
- `job-name` - название должности
- `salary_min` - минимальная зарплата
- `salary_max` - максимальная зарплата
- `personnel` - к какой категории относится вакансия: к среднему или старшему медицинскому персоналу (акушерские медсестры и врачи акушеры-гинекологи, соответственно)

## Методология

Рабочая тетрадь [`API OBGYN trudvsem.ipynb`](https://github.com/yanina-sorokina/glasnaya/blob/main/API%20OBGYN%20trudvsem.ipynb) производит следующий анализ:

##### Часть 1: Скачивание данных

##### Часть 2: Чистка и преобразование данных

##### Часть 3: Анализ данных

[`public data analysis.ipynb`](https://github.com/yanina-sorokina/glasnaya/blob/main/public%20data%20analysis.ipynb), в свою очередь, производит следующий анализ:

##### Часть 1: Осмотр и преобразование данных

##### Часть 2: Анализ данных

## Данные на выходе

Рабочая тетрадь [`API OBGYN trudvsem.ipynb`](https://github.com/yanina-sorokina/glasnaya/blob/main/API%20OBGYN%20trudvsem.ipynb) выводит датасет [`MAIN dataset with personnel.xlsx`](https://github.com/yanina-sorokina/glasnaya/blob/main/MAIN%20dataset%20with%20personnel.xlsx).

## Репликация анализа

Вы можете повторить анализ самостоятельно. Для этого на вашем компьютере должно быть установлено следующее:

- Python 3
- Библиотеки Python, указанные в [`API OBGYN trudvsem.ipynb`](https://github.com/yanina-sorokina/glasnaya/blob/main/API%20OBGYN%20trudvsem.ipynb) и [`public data analysis.ipynb`](https://github.com/yanina-sorokina/glasnaya/blob/main/public%20data%20analysis.ipynb)

## Лицензия

Весь код в этом репозитории доступен под лицензией [MIT License](https://opensource.org/licenses/MIT). Файл данных в папке output/ доступен по лицензии [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). Все файлы в папке data/ являются общественным достоянием.

## Отзывы / Вопросы?

Напишите Янине Сорокиной по адресу yanina.sorokina@protonmail.com

# Analysis of the shortage of obstetricians and gynecologists — Month Date, 2025

This repository contains data, analytic code, and findings that support portions of the article about the shortage of obstetricians and gynecologists, “[TKTKTKTK](https://friendly2.me/support/glasnaya/),” published **Month Date, Year**. Please read that article, which contains important context and details, before proceeding.

## Data

This analysis uses job vacancy data from the “Work in Russia” platform and Rosstat.

The spreadsheets come from the following sources:

- [Work in Russia platform](https://trudvsem.ru)
- [Unified Interdepartmental Information and Statistical System (EMISS)](https://fedstat.ru)

The resulting file [`MAIN dataset with personnel.xlsx`](https://github.com/yanina-sorokina/glasnaya/blob/main/MAIN%20dataset%20with%20personnel.xlsx), among others, the following columns relevant to the analysis:

- `id` - unique code for a vacancy
- `region_name` - name of the region where the job is posted
- `code_profession` - profession code according to OKPDTR (All-Russian Classifier of Professions, Positions, and Pay Grades)
- `job-name` - job title
- `salary_min` - minimum salary
- `salary_max` - maximum salary
- `personnel` - which category the vacancy belongs to: mid-level or senior medical personnel (obstetric nurses and obstetrician-gynecologists, respectively)

## Methodology

The notebook [`API OBGYN trudvsem.ipynb`](https://github.com/yanina-sorokina/glasnaya/blob/main/API%20OBGYN%20trudvsem.ipynb) performs the following analyses:

##### Part 1: Parsing data

##### Part 2: Cleaning data

##### Part 3: Analyzing data

[`public data analysis.ipynb`](https://github.com/yanina-sorokina/glasnaya/blob/main/public%20data%20analysis.ipynb), in turn, performs the following analysis:

##### Part 1: Data inspection and transformation

##### Part 2: Data analysis

## Outputs

The notebook [`API OBGYN trudvsem.ipynb`](https://github.com/yanina-sorokina/glasnaya/blob/main/API%20OBGYN%20trudvsem.ipynb) outputs the dataset [`MAIN dataset with personnel.xlsx`](https://github.com/yanina-sorokina/glasnaya/blob/main/MAIN%20dataset%20with%20personnel.xlsx).

## Running the analysis yourself

You can run the analysis yourself. To do so, you'll need the following installed on your computer:

- Python 3
- The Python libraries specified in [`API OBGYN trudvsem.ipynb`](https://github.com/yanina-sorokina/glasnaya/blob/main/API%20OBGYN%20trudvsem.ipynb) and [`public data analysis.ipynb`](https://github.com/yanina-sorokina/glasnaya/blob/main/public%20data%20analysis.ipynb)

## Licensing

All code in this repository is available under the [MIT License](https://opensource.org/licenses/MIT). The data file in the output/ directory is available under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

## Feedback / Questions?

Contact Yanina Sorokina at yanina.sorokina@protonmail.com
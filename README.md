# VacationPayCalculator
Spring-Boot 2.5.5 + Java 11 c одним API: GET "/calculacte?"
Приложение принимает среднюю зарплату за 12 месяцев и количество дней отпуска - отвечает суммой отпускных, которые придут сотруднику. При запросе также можно указать точные дни ухода в отпуск, тогда будет проводиться рассчет отпускных с учётом праздников и выходных.
localhost:8080/calculate?averageSalary=98000&vacationDays=14 Ответ: 46825.9385665529

localhost:8080/calculate?averageSalary=98000&vacationDays=14&startDate=2024-02-26 Ответ: 30102.389078498294

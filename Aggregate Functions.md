# EXERCISES


  >What database should I use for these exercises?
  Name: Employees
 



##### Question 1: What is the average salary for the company?
##### Table: > Salaries

```python
SELECT AVG(salary) FROM Salaries
```


##### Question 2: What year was the youngest person born in the company?
##### Table: employees

```python
SELECT MAX(birth_date) FROM employees

```


 >What database should I use for these exercises?
  Name: France
 


##### Question 1: How many towns are there in france?
##### Table: Towns
```python
SELECT COUNT(ID) FROM Towns
```




 > What database should I use for these exercises?
  Name: World
 


##### Question 1: How many official languages are there?
##### Table: countrylanguage
```python
SELECT COUNT(countrycode) FROM countrylanguage
WHERE isofficial = true
```

##### Question 2: What is the average life expectancy in the world?
##### Table: country
```python
SELECT AVG(lifeexpectancy) FROM country
```

##### Question 3: What is the average population for cities in the netherlands?
##### Table: city
```python
SELECT AVG(population) FROM city
WHERE countrycode = 'NLD'
```
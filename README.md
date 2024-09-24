SELECT *
FROM crime_scene_report where type='murder' and city='SQL City' and date=20180115

![image](https://github.com/user-attachments/assets/7bfa140e-65a8-46e3-8257-fdae568ba01e)


SELECT *
  FROM person where address_street_name='Northwestern Dr' or 'Franklin Ave'

SELECT *
  FROM person where address_street_name='Northwestern Dr'ORDER BY address_number DESC
limit 1

![image](https://github.com/user-attachments/assets/2fb4f0fd-7de4-4e1b-9815-47f2dd98f225)

              SELECT *
  FROM person where name like '%Annabel%' and address_street_name='Franklin Ave'
  
![image](https://github.com/user-attachments/assets/7b82c9c2-9b35-4504-9f61-2197d45bfd16)

SELECT *
  FROM interview where person_id=14887
  
  ![image](https://github.com/user-attachments/assets/0b402ac8-8c80-4a05-bf13-ad5af75075fe)


SELECT *
  FROM interview where person_id=16371
  
![image](https://github.com/user-attachments/assets/460fdff1-3dfb-4405-a883-5dc8ae0e202a)

SELECT * 
FROM get_fit_now_member 
where person_id=16371

![image](https://github.com/user-attachments/assets/f9166f85-eefc-4213-9ca5-fdae95a47948)

SELECT * 
FROM get_fit_now_check_in 
where check_in_date=20180109 and membership_id like'%48Z%'

![image](https://github.com/user-attachments/assets/1185fe99-ae7b-4913-a634-fb88408646cc)


SELECT * 
FROM get_fit_now_member 
WHERE id = '48Z7A' OR id = '48Z55'

![image](https://github.com/user-attachments/assets/3799c130-70a0-4d2b-9509-c5da7efa5803)

SELECT * 
FROM drivers_license 
where plate_number like '%H42W%'

![image](https://github.com/user-attachments/assets/9c017aa1-4704-43a7-b5ac-924c519f4968)


SELECT * 
FROM person 
where license_id=423327	 or license_id=664760	

![image](https://github.com/user-attachments/assets/16df07d4-370a-48fb-9c83-a81cf397994c)

SELECT * 
FROM person 
WHERE (license_id=423327 OR license_id=664760) AND (id=67318 OR id=28819);

![image](https://github.com/user-attachments/assets/7b94eb56-f8eb-4e6d-9cf0-386cef5ce9b8)

INSERT INTO solution VALUES (1, 'Jeremy Bowers');
 SELECT value FROM solution;
 
![image](https://github.com/user-attachments/assets/13b5c3da-e2f6-4f4a-b0ad-1861c0779ca7)

SELECT * FROM interview WHERE person_id = "67318";

![image](https://github.com/user-attachments/assets/220e2bf3-dce5-44dc-8a98-015e37481ede)

SELECT * FROM drivers_license WHERE gender = "female" AND hair_color = "red" AND height BETWEEN 65 AND 67 AND car_make = "Tesla" AND car_model = "Model S";

![image](https://github.com/user-attachments/assets/4fa15d28-a271-484d-b8ee-2bb71f10dc71)

SELECT * FROM person WHERE license_id IN ("202298", "291182", "918773");
![image](https://github.com/user-attachments/assets/ced679d3-9571-411c-8008-3bc379f07b1a)

SELECT person_id, event_name, COUNT(*) AS event_count FROM facebook_event_checkin WHERE person_id IN ("78881", "90700", "99716") GROUP BY person_id, event_name;

![image](https://github.com/user-attachments/assets/03577f9e-0f8b-42ee-b9e3-5ab2e9022ac3)

SELECT * 
FROM person
WHERE id = 99716;
![image](https://github.com/user-attachments/assets/8055ef0d-cfd3-4dc0-bb0f-07574c179443)

INSERT INTO solution VALUES (1, 'Miranda Priestly');
        SELECT value FROM solution;
![image](https://github.com/user-attachments/assets/77d7f83d-f190-4dad-a89e-3a79cc6ff438)


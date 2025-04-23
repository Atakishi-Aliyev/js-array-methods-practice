# js-array-methods-practice

---

### 📚 Array: `students`
```js
const students = [
  { id: 1, name: 'Aysel', age: 21, major: 'Computer Science', gpa: 3.6, attendance: 92, clubs: ['Robotics', 'Chess'] },
  { id: 2, name: 'Murad', age: 22, major: 'Mathematics', gpa: 3.9, attendance: 88, clubs: ['Math Club'] },
  { id: 3, name: 'Lale', age: 20, major: 'Physics', gpa: 3.4, attendance: 97, clubs: [] },
  { id: 4, name: 'Kamran', age: 23, major: 'Computer Science', gpa: 2.8, attendance: 75, clubs: ['Coding', 'Chess'] },
  { id: 5, name: 'Nermin', age: 21, major: 'Biology', gpa: 3.7, attendance: 98, clubs: ['Biology Club'] },
  { id: 6, name: 'Rauf', age: 22, major: 'Mathematics', gpa: 3.2, attendance: 85, clubs: ['Math Club', 'Coding'] },
  { id: 7, name: 'Zahra', age: 20, major: 'Physics', gpa: 3.9, attendance: 99, clubs: ['Astronomy'] },
  { id: 8, name: 'Elvin', age: 24, major: 'Biology', gpa: 2.9, attendance: 70, clubs: [] },
  { id: 9, name: 'Gunay', age: 22, major: 'Computer Science', gpa: 3.8, attendance: 94, clubs: ['Robotics'] },
  { id: 10, name: 'Javid', age: 23, major: 'Physics', gpa: 2.7, attendance: 80, clubs: ['Astronomy'] }
];
```

---

1. **Ortalama GPA-sı 3.5-dən yuxarı olan tələbələrin adlarını və ixtisaslarını qaytaran funksiya yazın.**

2. **Tələbələrin GPA və attendance dəyərlərinə əsasən akademik uğur skorunu (`gpa * attendance`) hesablayıb, bu skora görə azalan sırada sıralayan funksiya yazın.**

3. **Hər ixtisasa görə ən yüksək GPA-ya sahib olan tələbənin adını və GPA-sını qaytaran funksiya yazın.**

4. **Klublarda aktiv olan tələbələrin sayını və klub adlarını göstərən obyekt qaytaran funksiya yazın.**

   ```js
   {
     Robotics: 2,
     Chess: 2,
     ...
   }
   ```

5. **Ən çox kluba üzv olan tələbənin adını və klub sayını qaytaran funksiya yazın.**

6. **Əgər bir tələbənin həm GPA-sı 3.5-dən yuxarı, həm də attendance dəyəri 90-dan çoxdursa, bu tələbəni “Top Student” siyahısına əlavə edən funksiya yazın.**

7. **Tələbələrin yaş ortalamasını hesablayan bir funksiya yazın.**

8. **Eyni ixtisasa sahib tələbələri bir array-də qruplaşdırıb aşağıdakı formatda qaytaran funksiya yazın:**

   ```js
   {
     'Computer Science': ['Aysel', 'Kamran', 'Gunay'],
     'Mathematics': ['Murad', 'Rauf'],
     ...
   }
   ```

9. **Bütün tələbələrin GPA-sını 0.1 artıran, lakin maksimum 4.0-dan yuxarı getməyən yeni array qaytaran funksiya yazın.**

10. **Ən aşağı GPA-ya sahib tələbənin hansı klubda olmadığını və GPA-sını göstərən obyekt qaytaran funksiya yazın. (Əgər klubda yoxdursa, `['Robotics', 'Chess', ...]` kimi).**

---

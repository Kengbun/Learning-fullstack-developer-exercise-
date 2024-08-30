# Lab13 Object: Guess Result1				
บรรทัดที่มี * ให้ผลลัพธ์เป็นอะไร เพราะอะไร				
```				
"const product1 = { name: 'Coke', price: 18, size: '500mL' };

const product2 = product1;
product2.name = 'Pepsi';
product2.price = 19;

console.log(product1); // *  ผลลัพธ์ name: 'Pepsi', price: 18, size: '500mL' เพราะว่า มีการเปลียน ข้อมูล name  โดย product2
console.log(product2); // ** ผลลัพธ์ name: 'Pepsi', price: 18, size: '500mL' เพราะว่า product2 copy reference มาจาก product1
console.log(product1 === product2); // *** ผลลัพธ์ true เพราะ ที่อยู่ของข้อมูลเหมือนกัน  
"	
```							
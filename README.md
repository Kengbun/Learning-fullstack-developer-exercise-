# Lab 14 ES6: result4				
ผลลัพธ์ในบรรทัดที่มี * มีค่าเป็นอะไรและเพราะอะไร				
				
"let facts = { numPlanets: 8, yearNeptuneDiscovered: 1846 };
let { numPlanets, yearNeptuneDiscovered } = facts;
console.log(numPlanets); // * 8 
console.log(yearNeptuneDiscovered); // **  1846   
เพราะว่า let { numPlanets, yearNeptuneDiscovered } = facts; เป็นการ destructure object โดยนำค่าจาก facts มาเก็บไว้ในตัวแปรใหม่สองตัว "				
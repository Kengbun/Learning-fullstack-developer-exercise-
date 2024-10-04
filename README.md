# Lab 16 ES6: result6					
ผลลัพธ์ในบรรทัดที่มี * มีค่าเป็นอะไรและเพราะอะไร					
					
"function getUserData({ firstName, favoriteColor = 'green' }) {
  return `Your name is ${firstName} and you like ${favoriteColor}`;
}
getUserData({ firstName: 'Alejandro', favoriteColor: 'purple' }); // * 
"Your name is Alejandro and you like purple" เพราะฟังชัน  getUserData จะรีเทิน Your name is (parameters)  and you like (parameters) 

getUserData({ firstName: 'Melissa' }); // **
"Your name is Melissa and you like green"
เพราะไส่ parameter firstName แค่ตัวเดียว favoriteColor จึงได้ส่งค่า default ออกมาแทน

getUserData({}); // ***					
"Your name is undefined and you like green"
เพราะไม่ไส่ parameter ทั้ง2ตัว จึงรีเทินค่า default ออกมาแทน ในที่นี้ undefined คือค่าdefault ของ firstName 
"
# 	Lab19 Object: Guess Result4		
	บรรทัดที่มี * ให้ผลลัพธ์เป็นอะไร เพราะอะไร		
````			
	"var name = 'Joe';
function makeUser() {
  return {
    name: 'John',
    ref: this
  };
}
let user = makeUser();
console.log(user.ref.name); // *"ผลลัพธ์ Joe เพราะ เมื่อเรียกใช้ makeUser ฟังก์ชันจะถูกเรียกในบริบท global แล้ว this จะอ้างถึง global obj ซึ่ง global obj คือ name มี value ='Joe'
````		
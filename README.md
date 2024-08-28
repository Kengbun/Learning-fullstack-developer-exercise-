# js-lab-48
### Lab48 Object: Guess Result
บรรทัดที่มี * ให้ผลลัพธ์เป็นอะไร เพราะอะไร

```JavaScript
const user = {
  email: 'cc@gmail.com',
  isActive: true
};

user.isActive = false;
console.log(user); // *{email: 'cc@gmail.com', isActive: false} เพราะมีการเปลี่ยนแปลงค่าใน OBJ  
user = {};
console.log(user); // **error เพราะ ค่าตัวแปรที่ ประกาศด้วย const ไม่สามารถเปลี่ยนได้
```

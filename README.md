# ผลลัพธ์ในบรรทัดที่มี * มีค่าเป็นอะไรและเพราะอะไร				
				
"let [raindrops, whiskers, ...aFewOfMyFavoriteThings] = [
  'Raindrops on roses',
  'whiskers on kittens',
  'Bright copper kettles',
  'warm woolen mittens',
];
console.log(raindrops); // * 'Raindrops on roses'เพราะว่า เพราะถูกกำหนดค่าตามลำดับ ซึ่ง raindrops คือลำดับที่1 และ  'Raindrops on roses' ก็ลำดับที่1 จึงถูกจับคู่กัน

console.log(whiskers); // ** 'whiskers on kittens'เพราะว่า ตำแหน่ง หรือลำดับเหมือนกัน เหตุผลตามข้อแรก

console.log(aFewOfMyFavoriteThings); // *** 'Bright copper kettles',
  'warm woolen mittens' พราะว่า ตำแหน่ง หรือลำดับเหมือนกัน เหตุผลตามข้อแรก ส่วนที่เพิ่มมาคือ spread operator (...) จะเก็บค่าที่เหลือ           "				
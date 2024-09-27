# 	Lab22 Function: Fundamental3			
	"ผลลัพธ์ในบรรทัดที่มี * มีค่าเป็นอะไรและเพราะอะไร
"			
				
	"function makeWorker() {
  let name = 'Pete';
  return function () {
    alert(name);
  };
}
let name = 'John';
let work = makeWorker();
work(); // *"	Pete เพราะฟังก์ชันเข้าถึงตัวแปร name ที่มีอยู่ใน makeWorker		
##자바스크립트로 할수있는것들
* 웹, 앱, 리얼타임 게임, 다양한 것들을 할수있다. 서버도 만들수있다. 

##javascript version
* ES5,ES6등 specification하다 설명문 같은것이다.
* 명시를 받아서 자기마의 방식으로 표현하는것이 브라우저 이다. 

## vanilla 자바스크립트
* lib같은 것들이 없는 low js를 뜻한다. dom, jquery같은 것은 vanilla script를 다른식으로 변형한것이다. vanilla는 초당 operation이 가장 많다. 


## javascript variable
//변수를 초기화 하거나 생성할때 let을써야한다.
let a= 221;
let b= a-5;
a = 4; //updata var!
console.log(b ,a);
// line == expression 

## comment와 string 사용법
* c++이랑 똑같다 //를 사용해서 코멘트를 달고 변수 앞에 const를 달아 줄수도있다.

## array
* const monday = "Mon";
const tue = "Tue";
const wed = "Wed";
const thu = "The";
const fri = "Fri"; 

array
const daysOfWeek = ["Mon","Tue","Wed","Thu","Fri","Sat","Sun",true];
/*js 변수 규칙 첫문자는 소문자
띄어쓰기를 하고싶을땐 대문자*/
console.log(monday,tue,wed,thu,fri);
console.log(daysOfWeek);

배열의 인덱스도 가능하다. 

object 선언은 배열에서 {} 선언이다.
{name:"yoel",
age :33,
gender:"Male",
isHandsome:true}

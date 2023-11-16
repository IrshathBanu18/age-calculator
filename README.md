# 
To create a age calculator 
Using the Html,css,Javascript
-
- To run app
```
npx serve app
```
## To find age for person it calculate age month year 
For example

Enter your Date of Birth:16.06.2002
output is 21 years 4 months 19 days
Html for structures 
function getDaysInMonth(year, month) {
  return new Date(year, month, 0).getDate();
}

const date = new Date();
const currentYear = date.getFullYear();
const currentMonth = date.getMonth() + 1; // 👈️ months are 0-based

// 👇️ Current Month
const daysInCurrentMonth = getDaysInMonth(
  currentYear,
  currentMonth,
);
console.log(daysInCurrentMonth); // 👉️ 31

// 👇️ Other Months

const daysInJanuary = getDaysInMonth(2025, 1);
console.log(daysInJanuary); // 👉️ 31

const daysInSeptember = getDaysInMonth(2025, 9);
console.log(daysInSeptember); 
// 👉️ 30


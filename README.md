# Date-sort

var dates = [
 new Date(2007, 11, 10),
 new Date(2014, 2, 21),
 new Date(2009, 6, 11),
 new Date(2016, 7, 23)
];
dates.sort(function(a, b) {
 if (a > b) return -1;
 if (a < b) return 1;
 return 0;
});
// the date objects can also sort by its difference
// the same way that numbers array is sorting
dates.sort(function(a, b) {
 return b-a;
});

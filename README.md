# insertion-sort
[22,27,16,2,18,6] verisini ikili kontrol edeceği için adımlar şu şekilde olur;
[22,27,16,2,18,6] Step1
[22,16,27,2,18,6] Step2
[16,22,27,2,18,6] Step3
[16,22,2,27,18,6] Step4
[16,2,22,27,18,6] Step5
[2,16,22,27,18,6] Step6
[2,16,22,18,27,6] Step7
[2,16,18,22,27,6] Step8
[2,16,18,22,6,27] Step9
[2,16,18,6,22,27] Step10
[2,16,6,18,22,27] Step11
[2,6,16,18,22,27] Step12
Big-O Notation--> 1,2,3...12-->n*(n+1)/2--->n^2
18 sayısı sıralandıktan sonra ortada olacağı için average case durumuna girer.

[7,3,5,8,2,9,4,15,6] Selection sort adımları;
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
[2,3,4,5,6,7,8,15,9]
[2,3,4,5,6,7,8,9,15]

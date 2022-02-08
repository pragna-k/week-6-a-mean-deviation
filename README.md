# week-6-a-mean-deviation
f <- function(n){
  sum <- 0
  for(x in n){
    sum <- sum+x
  }
  mean <- sum/length(n)
  return(mean)
}
n=scan()
mean=f(n)
print(mean)
sum=0
for(i in 1:length(n)) {
  sum=sum+i
}
mean=sum/length(n)
x=0
for(i in 1:length(n)) {
  x=x+abs(i-mean)
 
}
meandeviation=x/length(n)
sprintf("mean deviation is %f",meandeviation)


OUTPUT:
> f <- function(n){
+   sum <- 0
+   for(x in n){
+     sum <- sum+x
+   }
+   mean <- sum/length(n)
+   return(mean)
+ }
> n=scan()
1: 5
2: 6
3: 8
4: 9
5: 4
6: 2
7: 3
8: 1
9: 
Read 8 items
> mean=f(n)
> print(mean)
[1] 4.75
> sum=0
> for(i in 1:length(n)) {
+   sum=sum+i
+ }
> mean=sum/length(n)
> x=0
> for(i in 1:length(n)) {
+   x=x+abs(i-mean)
+   
+ }
> meandeviation=x/length(n)
> sprintf("mean deviation is %f",meandeviation)
[1] "mean deviation is 2.000000"
> 

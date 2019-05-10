# hello-world
hello-world

// a little matlab
x = 5:0.2:25;
%{ 0<x<=10) x is from 5 => 25 %}
lamda = 0.5;
y = 1 - exp(-lamda*x);% y = P(X)
// figure
plot(x,y)
title('EXPONENTIAL DISTRIBUTION')
xlabel('Time')
ylabel('P(X)')

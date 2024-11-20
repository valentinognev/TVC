clear all
close all

x=145;
y=65;
theta=deg2rad(115);
phi=deg2rad(180);

A=x+y;
w=(x^2+2*A*y*cos(phi)-A^2-y^2)/2/(y*cos(phi)+x*cos(theta)-A);
z=A-w;

test1=x^2+w^2-2*x*w*cos(theta);
test2=z^2+y^2-2*z*y*cos(phi);
test1-test2
disp ''

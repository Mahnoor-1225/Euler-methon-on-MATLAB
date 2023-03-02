# Euler-methon-on-MATLAB
This is matlab code for Euler method used in numerical analysis .
%% Euler code %%
f=input('Enter your func')
t0=input('Enter initial values of independent variable: ')
yo=('Enter initial variable of dependent variable: ')
h= input('enter step size: ')
tn=input('Enter the poibnt at which we want to evaluate the solution: ')
n=((tn-to)/h)
t(1)=to;
for i=1:4
y(i+1)= y(i)+(h*f(t(i),y(i)))
t(i+1)=to*(i*h)
fprintf('y(%.2f)=%.4f\n',t(i+1),y(i+1))
end

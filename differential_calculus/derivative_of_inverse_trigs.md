### The Pythagorean identity
  
$$ \sin^2y+\cos^2y=1 $$
$$ \cos^2y=1-\sin^2y $$
$$ \cos\left(y\right)=\sqrt{1-\sin^2y} $$
$$ \sin^2y=1-\cos^2\left(y\right) $$
$$ \sin\left(y\right)=\sqrt{1-\cos^2\left(y\right)} $$


### Derivative of inverse sine

$$ y=\sin^{-1}x $$
$$ \sin\left(y\right)=x $$
$$ \frac{d}{dx}\left\lbrack\sin\left(y\right)\right\rbrack=\frac{d}{dx}\left\lbrack x\right\rbrack $$
$$ \cos\left(y\right)\cdot\frac{dy}{dx}=1 $$
$$ \frac{dy}{dx}=\frac{1}{\cos\left(y\right)} $$

Hence the trig identity above (Pythagorean)

$$ \frac{dy}{dx}=\frac{1}{\sqrt{1-\left(\sin^{}y\right)^2}} $$

Now remember `sin(y)=x`, first step above, and we substitute x

$$ \frac{dy}{dx}=\frac{1}{\sqrt{1-x^2}} $$



### Derivative of inverse cosine

$$ y=\cos^{-1}x $$
$$ x=\cos\left(y\right) $$
$$ \frac{d}{dx}\left\lbrack x\right\rbrack=\frac{d}{dx}\left\lbrack\cos y\right\rbrack $$
$$ 1=-\sin\left(y\right)\cdot\frac{dy}{dx} $$
$$ \frac{dy}{dx}=\frac{-1}{\sin\left(y\right)} $$

Hence the trig identity above (Pythagorean)

$$ \frac{dy}{dx}=\frac{-1}{\sqrt{1-\cos^{}\left(y\right)^2}} $$

Now remember `cos(y)=x`, first step above, and we substitute x

$$ \frac{dy}{dx}=\frac{-1}{\sqrt{1-x^2}} $$


### Derivative of inverse tangent

$$ \frac{d}{dx}\left\lbrack\tan x\right\rbrack=\sec^2\left(x\right)=\frac{1}{cos^2\left(x\right)} $$

Check trig identities to know where the sec came from

$$  y=\tan^{-1}\left(x\right)  $$
$$  x=\tan\left(y\right)  $$
$$  \frac{d}{dx}\left\lbrack\tan\left(y\right)\right\rbrack=\frac{d}{dx}\left\lbrack x\right\rbrack  $$

$$ \frac{1}{cos^2y}\cdot\frac{dy}{dx}=1 $$
$$ \frac{dy}{dx}=\cos\left(y\right)^2 $$

Dividing by 1 doesn't hurt anyone :D, the best part is 1 could be expressed in other forms :D

$$ \frac{dy}{dx}=\frac{\cos\left(y\right)^2}{1}=\frac{\cos\left(y\right)^2}{\cos\left(y\right)^2+\sin\left(y\right)^2} $$

Divide by `cos(y)^2`

$$ \frac{dy}{dx}=\frac{\frac{\cos\left(y\right)^2}{\cos\left(y\right)^2}}{\frac{\cos\left(y\right)^2}{\cos\left(y\right)^2}+\frac{\sin\left(y\right)^2}{\cos\left(y\right)^2}}=\frac{1}{1+\frac{\sin\left(y\right)^2}{\cos\left(y\right)^2}}=\frac{1}{1+\left(\frac{\sin\left(y\right)}{\cos\left(y\right)}\right)^2}=\frac{1}{1+\tan\left(y\right)^2} $$

Hence what x means above, it's tan(y), then subsititute and we are done!

$$ \frac{dy}{dx}=\frac{1}{1+x^2} $$
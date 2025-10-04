# Essential Logarithm (ln and log) Rules

The logarithm `ln(x)` is the natural logarithm, meaning its base is `e` and `e=(≈2.718)`.

`ln(x)` base is `e`, it's very important to understand the base when dealing with `ln`

## Product Rule
$$ \Huge \log_{b}\left(xy\right)=\log_{b}\left(x\right)+\log_{b}\left(y\right) $$
$$ \Huge \ln\left(xy\right)=\ln\left(x\right)+\ln\left(y\right) $$

## Quotient Rule
$$ \Huge \log_{b}\left(\frac{x}{y}\right)=\log_{b}\left(x\right)-\log_{b}\left(y\right) $$
$$ \Huge \ln\left(\frac{x}{y}\right)=\ln\left(x\right)-\ln\left(y\right) $$

## Power Rule (Crucial for 1^∞ Limits)
$$ \Huge \log_{b}\left(x^{k}\right)=k\log_{b}\left(x\right) $$
$$ \Huge \ln\left(x^{k}\right)=k\ln\left(x\right) $$

## Inverse Property (Crucial for Solving for L)
$$ \Huge b^{\log_{b}\left(x\right)}=x $$
* (*Hence the `e` and the base above!*)
$$ \Huge e^{\ln\left(x\right)=}x $$

## Identity Rule
$$ \Huge \log_{b}\left(b\right)=1 $$
$$ \Huge \ln\left(e\right)=1 $$

## Zero Rule
$$ \Huge \log_{b}\left(1\right)=0 $$
* (Hence any `b` here, any `log_b(x)`, where `x = 1`, is `zero`, even `e`)

## Change of Base Formula
While not strictly an *essential simplification rule*, the Change of Base Formula is critical for calculation when you need to convert a logarithm from an arbitrary base `b` to a more convenient base (like `e` or `10`) for calculation on a standard calculator.
$$ \Huge\log_{b}\left(x\right)=\frac{\log_{a}x}{\log_{a}b} $$
$$ \Huge \log_{b}\left(x\right)=\frac{\ln x}{\ln b} $$
---
description: Here we dive into the world of Hawking radiation
---

# Hawking Radiation

The metric representation for the stationary Schwarzchild black hole is expressed as

$$
ds^2=-\left(1-\frac{2M}{r}\right)dt^2+\frac{dr^2}{1-\frac{2M}{r}}+r^2\left(d\theta^2+\sin^2\theta d\varphi^2\right)
$$

where $$\sqrt{-g}=r^2\sin\theta$$.

Considering a scalar quantum field $$\phi(x,t )$$ in $$(3+1)$$-dimensional spacetime with Klein-Gordon equation of motion in curved space time

$$
\left(\square+m^2\right)\phi=0
$$

with d'Alembertian $$\square \equiv (\sqrt-g)^{-1}\partial_\mu\left[\sqrt{-g}g^{\mu\nu}\partial_{\nu}\right]$$.

Expanding the field in terms of an orthonormal basis of Klein-Gordon equation $$u_k(t,x)$$

$$
\phi=\int d³\mathbf{k}\left[\hat{a}_{\mathbf{k}} u_{\mathbf{k}}+\hat{a}_{\mathbf{k}}^{\dagger} u_{\mathbf{k}}^{*}\right]
$$

with annihilation and creation operators $$\hat{a}_{\mathbf{k}}$$, $$\hat{a}_{\mathbf{k}}^{\dagger}$$satisfying the canonical commutation relations. It is convenient to choose the set of modes $$\{u_{\mathbf{k}}\}$$ if it satisfies (at least asymptotically) an eigenvalue equation of the form $$i\partial_{\tau}u_k =\omega_k u_k$$, where $$\partial_{\tau}$$is some (possibly global) time-like Killing vector and $$\omega_k$$ is a real eigenvalue.&#x20;

Searching for solutions $$\phi = \frac{1}{\sqrt{2\pi\omega_k}}e^{-i\omega_k t}f_{\omega l}(r)Y_{lm}(\theta,\varphi)$$ in the wave equation we obtain&#x20;

$$
\frac{fe^{-i\omega t}}{\sqrt{2\pi \omega}r^2} \left\{\frac{1}{\sin\theta}\frac{\partial}{\partial \theta}\left(\sin\theta\frac{\partial Y}{\partial \theta}\right)+\frac{1}{\sin^2\theta}\frac{\partial^2Y}{\partial \varphi^2} \right. \\ \left.+\left[\frac{1}{f}\frac{d}{dr}\left(r²\left(1-\frac{2M}{r}\right)\frac{df}{dr}\right)+\left(\frac{\omega^2}{1-\frac{2M}{r}}+m²\right)r^2\right]Y\right\}=0.
$$

Which satifies the spherical harmonic EDP if

$$
\left[\frac{1}{f}\frac{d}{dr}\left(r²\left(1-\frac{2M}{r}\right)\frac{df}{dr}\right)+\left(\frac{\omega^2}{1-\frac{2M}{r}}+m²\right)r^2\right]=l(l+1)
$$

or

$$
\frac{1}{r^2}\frac{d}{dr^{*}}\left(r^2\frac{df}{dr^{*}}\right)+\eta^2(r)f-\frac{l(l+1)}{r^2}\left(1-\frac{2M}{r}\right)f =0.
$$

where $$\partial r/\partial r^{*}=(1-\frac{2M}{r})$$ in the Tortoise coordinates and $$\eta(r)=\sqrt{\omega^2+\left(1-2M/r\right)m^2}$$

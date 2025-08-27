# Maxwell Denklemleri ve Düzlemsel Dalga

Aşağıda SI birimlerinde diferansiyel formda Maxwell denklemleri verilmiştir:

$$
\nabla \cdot \mathbf{D} = \rho,\qquad
\nabla \cdot \mathbf{B} = 0,\qquad
\nabla \times \mathbf{E} = -\,\frac{\partial \mathbf{B}}{\partial t},\qquad
\nabla \times \mathbf{H} = \mathbf{J} + \frac{\partial \mathbf{D}}{\partial t}.
$$

İzotropik, kayıpsız ortamda $ \mathbf{D}=\varepsilon \mathbf{E} $, $ \mathbf{B}=\mu \mathbf{H} $.

## Problem

Homojen ortamda $+\hat{\mathbf{z}}$ yönünde yayılan frekansı $ \omega $ olan düzlemsel bir dalga için
elektrik alanın fazör temsili
$$
\tilde{\mathbf{E}}(z) = \tilde{E}_0\, e^{-j k z}\, \hat{\mathbf{x}}
$$
olsun.

1. Manyetik alan fazörünü $ \tilde{\mathbf{H}}(z) $ bulun.
2. Faz hızı ve dalga boyunu ortam parametreleri cinsinden yazın.

## Çözüm

Faraday yasasının fazör formu:
$$
\nabla \times \tilde{\mathbf{E}} = -j\omega \tilde{\mathbf{B}} = -j\omega \mu \tilde{\mathbf{H}}.
$$
Verilen $ \tilde{\mathbf{E}} $ için $ \nabla\times\tilde{\mathbf{E}} = -jk \tilde{E}_0 e^{-jkz}\, \hat{\mathbf{y}} $ olur.
Dolayısıyla:
$$
-jk \tilde{E}_0 e^{-jkz}\, \hat{\mathbf{y}} = -j\omega \mu \tilde{\mathbf{H}}
\quad\Rightarrow\quad
\tilde{\mathbf{H}}(z) = \frac{k}{\omega \mu}\, \tilde{E}_0 e^{-jkz}\, \hat{\mathbf{y}}.
$$

Dalgada $ k=\omega \sqrt{\mu\varepsilon} $ olduğundan:
$$
\tilde{\mathbf{H}}(z) = \frac{1}{\eta}\, \tilde{E}_0 e^{-jkz}\, \hat{\mathbf{y}},
\quad \eta = \sqrt{\frac{\mu}{\varepsilon}}.
$$

Faz hızı $ v_p $ ve dalga boyu $ \lambda $:
$$
v_p = \frac{\omega}{k} = \frac{1}{\sqrt{\mu\varepsilon}}, 
\qquad
\lambda = \frac{2\pi}{k} = \frac{2\pi}{\omega} v_p.
$$

> Not: Boşluk için $ \mu=\mu_0 $, $ \varepsilon=\varepsilon_0 $ ve $ \eta \approx 377\,\Omega $.

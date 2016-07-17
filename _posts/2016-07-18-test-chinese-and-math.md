---
layout: post
title: 中文+数学
description: "Sample post with a background image CSS override."
tags: [sample post]
categories: [math, test]
comments: true
image:
  background: triangular.png
---
<!-- mathjax config similar to math.stackexchange -->
  <script type="text/x-mathjax-config">
   MathJax.Hub.Config({
     TeX: {
        equationNumbers: {
         autoNumber: "AMS"
        }
      }
    });
  </script>


   <script type="text/x-mathjax-config">
 	 MathJax.Hub.Config({
      tex2jax: {
       inlineMath: [ ['$','$'], ["\\(","\\)"] ],
       processEscapes: true
      }
     });
   </script>

   <script type="text/x-mathjax-config">
     MathJax.Hub.Config({
        tex2jax: {
         skipTags: ['script', 'noscript', 'style', 'textarea', 'pre', 'code']
        }
     });
  </script>

  <script type="text/x-mathjax-config">
     MathJax.Hub.Queue(function() {
         var all = MathJax.Hub.getAllJax(), i;
          for(i=0; i < all.length; i += 1) {
             all[i].SourceElement().parentNode.className += ' has-jax';
          }
      });
  </script>

  <script type="text/javascript"
    src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
  </script>

数学

\begin{equation}\label{eq:1}
\left( \sum_{k=1}^n a_k b_k \right)^{2} 
\leq 
\left( \sum_{k=1}^n a_k^2 \right) 
\left( \sum_{k=1}^n b_k^2 \right)
\end{equation}

[download](\files\2016-2017_summer_course\6_4.pdf)

Here \eqref{eq:1} is ...

[download](\files\2016-2017_summer_course\6_4.pdf)

inline equation $a^2+b^2=c^2$

[download](\files\2016-2017_summer_course\6_4.pdf)

displayed equaton


\\[\int_\Sigma fd\mu\\]

[download](\files\2016-2017_summer_course\6_4.pdf)
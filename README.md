# nginx_ssllabs_A+

Finally got a perfect score on ssllabs. By the time you're reading this ssllabs may have changed their criteria making this no longer a 400/400 winner, but it's good as of 03 May 2018. Go with 4096, anything higher is overkill, slower, will break compatibility with old browsers and won't impress ssllabs. That may change in the future however, as it did with 2048 which used to be high enough. 

In addition to perfecting your ssl implementation, consider submitting your site to https://hstspreload.org/ for HSTS so that Chrome and other browsers will upon installation instruct browsers to jump straight to https when loading your domain as a means of dodging MITM ssl stripping attacks.

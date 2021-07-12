---
layout: post
title: 🖥️ Passing the AZ-104
description: The Microsoft AZ-104 exam and my experience from a general sysadmin perspective, including study techniques and complaints.
comments: true
---

So after a while of panic and dread, I passed my Microsoft AZ-104 exam and to be honest, it wasn't actually that bad!
I started properly investing myself into the AZ-104 exam after Microsoft Ignite 2021 provided free exam vouchers for individuals who complete the yearly Ignite challenge, I was already looking at it but I guess you could say this finally pulled me in to do it!

A couple of people have already asked for exam advice, whilst I'm definitely not an educator in the subject, the number one thing I would say to someone going to do the AZ-104 would be to book it as soon as you can! As someone who is not a fan of exams, I continuously put it off but in reality it forced me to be productive. Admittedly, it's not the best idea to make yourself anxious or nervous but it did make me study a lot more than I already was doing.

I work with Azure on an almost daily basis so I'd like to think I have a good understanding of how most of the things in the spec work, with the exception of a few things that were already set up in my organisation, some of the things I learned during my training have now been implemented into our Azure environment.

My study resources primarily consisted of Pluralsight (shoutout Tim Warner and Michael Bender!), which was paid for by my employer. I whole-heartedly recommend tinkering with your own lab environment, I feel with tech training, that is where you will get the majority of your knowledge and experience. However, I do accept a lot of people won't have the compute resources to tinker with the on-prem aspects, instead I did a lot of self-paced training in Azure directly by using Spot instances to minimise costs, the highest it went to before I sat the exam was just under £14, which, for the knowledge and certification that brought me, I think was money well spent.


![Microsoft Certified Azure Administrator](/public/azure-administrator-associate.png){:class="img-responsive"}

{% if page.comments %}
<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://morganfell-dev.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}
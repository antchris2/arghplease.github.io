---
layout: page
title: Machine Learning Harmonizer Plugin
img: assets/img/ableton.png.webp
importance: 2
category: work
---


I've always been someone interersted in seeing how novel technology is used within art and I'm especially curious how now and in the future new genres ways of music making will come to exist. Over the past year or so however, I found myself dismayed at how some of the newest and most powerful technologies, as soon as they were unleashed on the general public, were immediately used to replace rather than augment artists. Therefore, for my senior thesis in Computing and the Arts at Yale University, I chose to make this tool that leverages transformer-based architectures through PyTorch with Ableton Live and MaxMSP to create a plugin that generates harmonies as a creative tool to help composers.


Here's a demo where the model generates progressively more dissonant harmonizations of a melody by changing the "temperature" value, a common parameter in machine learning that in this case equates to lower temperature values yielding more boring, conventional harmonies and higher values yielding more dissonant but potentially more interesting possibilities for composers and musicians. 

<iframe target="_parent" width="640" height="480" src="https://www.youtube.com/embed/bnd53gVVSGk?si=GfuYT0JaMbRxHeOI?enablejsapi=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Code here: 

https://github.com/antchristou/Melody-Harmonization

Generative Adversarial Networks are a type of artificial intelligence that can generate fake images that appear convincingly
real. Until GANs were invented, artificial intelligence was not yet capable of imagination. Now, GANs can be used to create
everything from artwork to faces of celebrities that don’t actually exist. There are two opposing networks in a GAN - a
generator, and a discriminator. p(y|x) The generator is responsible for creating random images, and the discriminator is
responsible for deciding which look real and which don’t. The generator is fed a random noise signal, which it transposes into
pixels through a 4-layer process of convolutions. The generator tries to maximize the probability of producing an image that
matches certain criteria for the discriminator. This is done through a p(y|x) (probability of y given x) type of function. For
instance, the probability of producing a cat given that this image contains ears, or p(cat|ears). The discriminator then takes
this generated image of a cat and compares it to multitudes of real images of cats (also using probability functions and 4
convolution layers). After assessing the fake image from the generator, the discriminator signals that either the image is
convincing or unconvincing.
The idea of adversarial networks was half-conceptualized in the 1960s, but due to lack of resources, wasn’t fully realized. Later
on it was reinvented by Jurgen Schmidhuber in 1990. He came up with the idea of opposing neural networks, called Net 1 and Net 2.
Then, in 2014, Ian Goodfellow with help from a team of other computer scientists further developed this idea and coined the term
General Adversarial Networks. He now works for the Google Brain team, and had just received a PhD from the University of Montreal
before inventing GANs.
GANs have been used for a variety of purposes. A computer-generated painting called Edmond de Belamy sold for $432,000 in 2018,
which has led to very interesting discourse on how the value of art is changing in the digital age. There is a scary possibility
that GANs will put artists and designers out of work - GANs can now auto-generate video game characters, design graphics, and
compose music. MidiNet is an example of a GAN that can generate melodies. They’ve even been used to style outfits, like with
DiscoGAN, a adversarial network that can select clothes based on style, color, texture, and compatibility.
GANs fall under the category of strong AI - this type of AI can remember past information in order to complete tasks, whereas
weak AI (a bot that plays chess, for example) will not remember past information. GANs are also a form of machine learning AI -
this type of AI learns by itself and improves over time in order to complete a set goal. Self-driving cars fall under this
category.
Sources: https://medium.freecodecamp.org/an-intuitive-introduction-to-generative-adversarial-networks-gans-7a2264a81394
https://medium.com/technology-invention-and-more/everything-you-need-to-know-about-artificial-neural-networks-57fac18245a1
https://www.technologyreview.com/s/610253/the-ganfather-the-man-whos-given-machines-the-gift-of-imagination/
https://arxiv.org/abs/1406.2661
https://en.wikipedia.org/wiki/Generative_adversarial_network
https://medium.com/@jonathan_hui/gan-some-cool-applications-of-gans-4c9ecca35900
https://www.scientificamerican.com/article/spot-the-fake-artificial-intelligence-can-produce-lifelike-photographs/

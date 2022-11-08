# cal_mean_spec_py
This code is for creating the input *.cxt files of the STARLIGHT programme. We need to calculate the mean spectrum of the data from SDSS. 

Because of the spectra data from the SDSS is in the "loglam" format (without th erest-frame wavelengths in units 'Angstorm'), we cannot input the spectra data directly into STARLIGHT.

There are also many codes on Github which can automatically calculate the wavelengths/flux and produce suitable input *.cxt file for STARLIGHT.

But these codes are all in IDL and without being maintained for a long time.

Consequently, running these codes could be tough! 

There still exit IDL codes which could run well and automatically by Xueguang Zhang (Nanjing Normal University) with a few setups.

The IDL code mentioned above could be found in Zhang's newly published book in China(mainland). I strongly recommend Chinese readers who are interested in SDSS get one because it is really useful and could be used as a handbook in your research.

As to this code I present here, it is just a humble method and just includes the basic commands in Python.

If the number of your targets is not too much and you are now having no way of handling the spectra files to input into the STARLIGHT, maybe you can try this one.

Last but most important, if you have a better way of achievement, please let me know!!!
(my e-mail: phylmf@njnu.edu.cn)

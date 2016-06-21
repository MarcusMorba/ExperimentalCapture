# Multispectral & Hyperspectral Imaging

![Electromagnet_spectrum](http://stopocsmartmeters.com/uploads/3/5/1/6/3516580/7934370_orig.jpg)

![Nasa_spectrum](https://www.nasa.gov/sites/default/files/spectrum_wall_chart_aug2011.jpg)

[*Multispectral imaging*](https://en.wikipedia.org/wiki/Multispectral_image) employs additional channels of electromagnetic radiation beyond human perception, such as infrared (IR), ultraviolet (UV), X-rays, and more. 

[*Hyperspectral imaging*](https://en.wikipedia.org/wiki/Hyperspectral_imaging) attempts to capture the entire reflective or emissive spectrum for every pixel, essentially representing an image with a three-dimensional (x,y,λ) data cube.

This lesson includes a discussion of the following: 

* Overview of Multi/Hyperspectral Imaging
* Near-Infrared (NIR) Imaging
* X-Ray Imaging
* Thermal Imaging
* Thermochromic Imaging
* Ultraviolet (UV) Imaging
* Radar 
* Millimeter Wave & Terahertz Imaging
* CT Scans, MRI, CAT Etc.

In addition, two other imaging techniques, while not properly multi-spectral, deal with unusual properties of light and its transmissive medium: 
* Polarized Light
* Schlieren Photography

Finally, it's not even necessary to image with electromagnetic radiation; let's not forget about sound. 

* Sonar and Ultrasonic Imaging


--- 

### Overview. What does it look like? 

Because the human eye cannot see X-rays, long-wave infrared, ultraviolet light, and so forth, an imaging technology is required to translate energy patterns in these spectra into patterns we can see. The "right" way to visualize such energy patterns is always arbitrary, or, at least, an artifact of the sensing and display technology. 

![Multi-spectral face](images/face-spectra.jpg)<br />
*A face simultaneously imaged in the (a) visible spectrum, 0.4–0.7 µm, (b) short-wave infrared, 1.0–3.0µm, (c) mid-wave infrared, 3.0–5.0µm, and (d) long-wave infrared, 8.0-14.0µm.*

* [An excellent paper on multispectral face recognition](http://www.intechopen.com/books/reviews-refinements-and-new-ideas-in-face-recognition/thermal-infrared-face-recognition-a-biometric-identification-technique-for-robust-security-system)
* [Differences between UV, Vis, NIR (Wikipedia)](https://en.wikipedia.org/wiki/Full-spectrum_photography#/media/File:UV_Vis_IR_Portrait.jpg)
* More [faces viewed in multiple spectra](https://www.flickr.com/photos/rshephorse/4279928945)

![Hyperspectral face by RShephorse](images/hyperspectral-face-rshephorse.jpg)

--- 

### Some applications

* Satellites employ multispectral imaging to understand the Earth. [Charlie Loyd, Putting Landsat8's multispectral imaging to work.](https://www.mapbox.com/blog/putting-landsat-8-bands-to-work/). For example, here's a false-color Landsat8 image by in which SWIR (thermal) is used in the red channnel; NIR as green; and deep blue as blue:

![False-color image using thermal data in the red channel](https://farm3.staticflickr.com/2806/9027218111_70b9afb012_o.jpg)

* Astronomers use multispectral imaging to [understand the Sun](http://www.nasa.gov/images/content/719688main_Sun-Wavelength-Chart_full.jpg). 

![Multispectral image of the sun](http://www.nasa.gov/images/content/719688main_Sun-Wavelength-Chart_full.jpg)

* Forensic specialists use infrared and ultraviolet imaging and/or fluorescence to [recover writing lost to water damage](https://people.rit.edu/andpph/photofile-b/ir-letter-comparison-1.jpg), [analyze medieval frescoes](https://artcosnervationcsmodotcom.wordpress.com/category/rti/), [detect fraudulent documents](https://www.fbi.gov/about-us/lab/forensic-science-communications/fsc/oct1999/images/inkglowb.jpg), [determine the provenance of artifacts](https://www.fbi.gov/about-us/lab/forensic-science-communications/fsc/oct1999/images/matchb.jpg), [sort fragments of shredded documents](https://www.fbi.gov/about-us/lab/forensic-science-communications/fsc/oct1999/images/shredb.jpg), [detect underpaintings in famous artworks](http://www.artic.edu/collections/conservation/revealing-picasso-conservation-project/examination-techniques/infrared), [detecting previous versions of artworks (includes web interactive)](http://www.webexhibits.org/pigments/intro/visible.html).

![IR image of water-damaged document](https://c2.staticflickr.com/8/7756/27807952145_7089ed4630_o.jpg)

![Using IR to detect fraud](https://c2.staticflickr.com/8/7284/27529572880_f5ce290cbf_o.jpg)

![Using UV fluorescence to distinghuish different fragments of white paper](https://c2.staticflickr.com/8/7429/27807952055_e1024c7137_o.jpg)

---

### Near-Infrared (NIR) Imaging

Near-infrared is widely used in security cameras. 

* Owing to the different infrared reflectivity of blood, you can [see veins easily](https://www.flickr.com/photos/nebarnix/2034727799) in NIR.

![Veins, in NIR by Jasper Nance](images/nir-veins.jpg)

* This has been used in some medical AR applications, such as the Christie [VeinViewer](http://www.bayareahospital.org/Images/IV_Insertions_Get_Easier_For_Patients.aspx) device. 

![The VeinViewer visualizes an IR image with an augmented projection](https://c2.staticflickr.com/8/7706/27529572870_bb07b07e7b_b.jpg)

* In some circumstances, depending on materials, NIR cameras can [kind of see through clothes](http://www.komonews.com/news/problemsolvers/94802064.html). 

* NIR imaging can be used to [detect traced (i.e. forged) signatures](https://www.fbi.gov/about-us/lab/forensic-science-communications/fsc/oct1999/images/tracingb.jpg)

![Forged signatures in IR](https://c2.staticflickr.com/8/7286/27706929542_0d7949d045_o.jpg)

* Osman Khan created a strictly [IR-viewable image](http://www.osmankhan.com/works.asp?name=Unviewed).
* The paintings [*"The Lynching of Leo Frank"*](http://www.oliverlutz.com/oliverlutz_prjct_lfrnk.htm) and [*"Stella at the Playground"*](http://www.oliverlutz.com/oliverlutz_prjct_plygrnd_inst.htm) by Oliver Lutz (2010) use a (visibly) black acrylic overpainting covering a secret image that can only be observed by a NIR security camera and a nearby CCTV. Lutz makes [many projects](http://www.oliverlutz.com/oliverlutz_prjct_nscr.htm) with this IR-clear, visibly-black overpainting. His work appeared in the exhibition [*"Exposed: Voyeurism, Surveillance and The Camera since 1870"*](http://www.walkerart.org/calendar/2011/exposed-voyeurism-surveillance-and-the-camera). 

![Paintings by Oliver Lutz](https://c2.staticflickr.com/8/7423/27196695613_494e63d02b_o.jpg)

* Richard Mosse's *[The Enclave](https://vimeo.com/67115692)* (2013) is a documentary film about the ongoing civil war in Congo, shot on infrared color film. 

![Richard Mosse's 'The Enclave'](https://c2.staticflickr.com/8/7229/27808128055_55bf700b48_o.png)

* Hey, here's an [infrared time-lapse](https://vimeo.com/58232705) video by Andrew Shurtleff.

![Still from NIR time-lapse by Andrew Shurtleff](https://c2.staticflickr.com/8/7674/27196814663_85e0036718_o.png)

---

### X-Ray imaging

#### X-Ray Imaging in the Arts

* [X-ray portraits by Ayako Kanda and Mayuka Hayashi](http://www.boredpanda.com/x-ray-couple-portraits-ayako-kanda-mayuka-hayashi/)

![X-ray portraits by Ayako Kanda and Mayuka Hayashi](https://c2.staticflickr.com/8/7198/27196288194_c64b8f810a_b.jpg)

* [*Lick* by Wim Delvoye](http://curiator.com/art/wim-delvoye/lick-1)

![Lick by Wim Delvoye](https://c2.staticflickr.com/8/7392/27707261232_b627010ce9_b.jpg)

* [*Pinup Calendar* by German ad firm, BUTTER](http://www.themarysue.com/x-ray-pin-up-calendar/)

![Pinup Calendar by BUTTER](https://c2.staticflickr.com/8/7298/27196288294_99546c5c9c_o.jpg)

* [Xograms, by Hugh Turvey](http://www.smithsonianmag.com/arts-culture/x-ray-art-deeper-look-everyday-objects-180949540/?no-ist)

* [*X-Ray Photographic Art* (Survey)](http://www.theapricity.com/forum/showthread.php?147702-X-Ray-Photographic-Art-Seeing-Humans-Nature-Objects-Beneath-The-Surface)

It is also possible to design or arrange objects for the express purpose of having them discovered in X-Ray images. 
* Arguably some of these people have done so. (X-ray insertions)
* Evan Roth, TSA interventions

---

### Thermal Imaging 

![Thermal image](images/thermal-img.jpg)

*Thermal imaging* senses light wavelengths in the range of ~8000-14000 nanometers, also called *long wave infrared*, which corresponds to what we experience as *heat*. Interestingly, most of what we see when we observe radiation in this range is *emissive* rather than *reflective*. In short, we see where something is hot. 

* A cult classic, [*THE OPERATION*](https://vimeo.com/24149525) by Jacob Pander and Marne Lucas (1995) is a hybrid art/porn movie, shot completely with a thermal camera. (NSFW)
* [Route 94: *My Love*](https://vimeo.com/84702235) is a much more recent music video with much the same idea. 

![City Thermogram by Peggy Ahwesh](images/terike-haapoja-thermal.jpg)

* Terike Haapoja's [*Community* (2007)](http://www.av-arkki.fi/en/works/community_en/) presents thermal videos of animals which have just died. We see the heat leaving their bodies. 
* [This Photographer Shoots Portraits With a Thermal Camera](http://www.smithsonianmag.com/science-nature/this-photographer-shoots-portraits-with-a-thermal-camera-1437109/)
  * [Linda Alterwitz 1](http://www.lindaalterwitz.com/thermal_portrait.html)
  * [Linda Alterwitz 2](http://www.lindaalterwitz.com/thermal_core.html)

Note that there is no "correct" way to view thermal imagery. Cameras offer a variety of different spectra for mapping their temperature ranges, including grayscale, black-body, chromatic (blue = cold), etc. 

![City Thermogram by Peggy Ahwesh](images/ahwesh-city-thermogram.jpg)

Sometimes simply presenting such alternative views can be a provocative, entertaining or educational experience for audiences. 

* Many science museums, such as the Exploratorium, have a "[Heat Camera](http://exs.exploratorium.edu/exhibits/heat-camera/)" display in which the public can see themselves in a thermal camera. 
* *[City Thermogram](http://thecreatorsproject.vice.com/blog/times-square-is-a-heat-sensitive-camera-thanks-to-peggy-ahwesh)*, by Peggy Ahwesh (2015), was commissioned to create a live-video installation in New York's Time Square, in which she connected up a thermal camera (trained on passersby) to a large electronic billboard.
* Google has recently made [satellite thermal imaging of roofs](http://mashable.com/2015/08/20/google-house-solar/?utm_cid=mash-com-fb-main-link) available to the public, to prompt people's awareness about the  heat inefficiency of their homes. 


---

### Thermochromic Imaging

Some substances temporarily change color in response to heat. In different contexts, thermochromic pigments can work as a capture technology or a display technology. 

* Jay Watson's *[Thermochromic Table](http://www.fubiz.net/en/2014/02/21/thermochromic-table/)* (2011) reveals where and how people have sat at the furniture. 
* The *[Temperature Sensitive Object](http://www.mascontext.com/wp-content/uploads/2011/12/12_game_ornaments_09.jpg)* chair (2001) by Orléans-based design group, Archilab, is similar. 
* The revelatory potential of this technology is directly connected to considerations of mammalian territory-marking behavior in this *[thermochromic toilet seat](http://theluxuryofprotest.com/Thermochromic_Toilet_Seat.html)* and this remarkable *[thermochromic urinal](http://www.technocrazed.com/wp-content/uploads/2014/08/New-Thermochromic-Furniture-And-Pots-11.jpg)*
* Dutch artist [Carina Hesper](http://carinahesper.nl) has created a book, *[Like a Pearl in My Hand](http://www.carinahesper.nl/#!visually-impaired)*, in which portrait photographs have been overprinted with thermochromic coating. The reader of the book must interactively reveal the underlying photographs 

---

### Ultraviolet (UV) Imaging 

#### Ultraviolet animal vision. 

* Many animals [can see in the ultraviolet](http://www.theatlantic.com/technology/archive/2011/08/6-animals-that-can-see-or-glow-in-ultraviolet-light/243634/). 
* [Spectra of different species' vision](https://fieldguidetohummingbirds.files.wordpress.com/2008/11/spectrum.jpg).
* [Birds & bees' UV vision](http://www.nature.com/scitable/blog/the-artful-brain/alternate_realities)

UV is also [widely used in forensics](http://ultravioletcameras.com/applications/longwave-ultraviolet-forensics-imaging-applications/). 

#### Artworks using UV

* [UV video overview](https://www.youtube.com/watch?v=o9BqrSAHbTc)
* [Thomas Leveritt, *Nivea Australia spot*](http://www.leveritt.com/page-uv/)
* [UV portraits by Cara Phillips](http://www.theguardian.com/artanddesign/gallery/2012/aug/03/ultraviolet-beauties-cara-phillips-photographs)

#### UV imaging in practice

* [UV-pass, visible-cut filters](http://www.savazzi.net/photography/baader_u.htm) are available. 
* It is also relatively inexpensive to have a [Canon SLR permanently converted for UV](http://www.lifepixel.com/shop/ultraviolet-camera-conversion/canon-dslr-uv-camera-conversion). 
* It is [worth pointing out](http://www.savazzi.net/photography/uv.htm) that UV & NIR photography also benefit from using [special lenses](http://www.savazzi.net/photography/coastalopt_60.html) which better focus these wavelengths. 
* Of course, [dedicated UV cameras](http://www.edmundoptics.com/cameras/nir-uv-cameras/sony-xc-e-series-monochrome-ccd-cameras/56346/) also exist. 

---
### Radar

[From [Wikipedia](https://en.wikipedia.org/wiki/Radar)] **Radar** is an object-detection system that uses radio waves to determine the range, angle, or velocity of objects. It can be used to detect aircraft, ships, spacecraft, missiles, motor vehicles, weather formations, and terrain. A radar transmits radio waves or microwaves that reflect from any object in their path. 

![Marine radar](images/marine-radar.jpg)<br />

**Marine radar** is surprisingly inexpensive and produces fascinating images of the world, allowing (for example) imaging of nearby whales. Devices such as the [Furuno 1623](http://www.thegpsstore.com/Furuno-1623-22-kw-Radar-P125.aspx) or Furuno DRS4W systems cost under $1500. 

![Ground penetrating radar](images/ground-penetrating-radar.jpg)<br />*(Image from [here](http://www.malags.com/getattachment/Innovation/GPR-Explained/MALA-GPR-principle.jpg)).*

**Ground-penetrating radar** images features such as underground pipes. Speak to the professor if you're interested in this; we have a contact at Pittsburgh-area providers, [Geospatial Corporation](http://www.geospatialcorporation.com/).

--- 
### And Beyond...


#### Millimeter Wave & Terahertz Imaging

![Terahertz imaging](images/terahertz-imaging.jpg)

This is the stuff that *really* sees through clothing. 

* [Millimeter wave scanners](https://en.wikipedia.org/wiki/Full_body_scanner#Controversies), also called backscatter imaging, are used by the TSA 
* [Terahertz imagers](http://www.stamparein3d.it/wp-content/uploads/2015/04/Lenti-a-Onde-THZ-05.jpg), which operate around 300 micrometers.

Indeed, it can see through [more than just clothing](http://www.propublica.org/article/drive-by-scanning-officials-expand-use-and-dose-of-radiation-for-security-s). 

![Backscatter examination of truck with illegal immigrants](images/backscatter-truck.jpg)<br />
*"Treating people like luggage"*

#### CT Scans, MRI, CAT etc. 

X-ray computed tomography (X-ray CT) and magnetic resonance imaging (MRI) and are medical imaging techniques that employ significant computation to produce 3D models of internal body structures and activities. Perhaps if you have a good reason, you can get a scan of yourself at the hospital. 

![Kyle McDonald CT scan](images/kyle-mcdonald-ct-scan.jpg)<br />
*Kyle McDonald experimenting with some of his own CT scan data in openFrameworks.*

---

### Polarized Light

Polarization is a property of light which describes, not its frequency or wavelength, but the orientation of the spatial plane in which its waves are traveling. It is useful in visualizing several phenomena which cannot otherwise be seen by the human eye. 

![Polarized light eliminates reflections](images/circular-polarizer.jpg)<br />
Polarized light eliminates reflections. Here, a circular polarizer eliminates reflections on water, making another world visible beneath. From ["Removing Glare with a Circular Polarizer"](https://nicolesyblog.com/2014/07/24/removing-glare-with-a-circular-polarizer-filter/), which includes a nice [video](https://www.youtube.com/watch?v=ZC6DNx0F1o0). 

By computing the difference between images of scenes taken with and without polarizations, it's possible to cleave the diffuse appearance of an object from its specular appearance. The images below, taken from "[How To Split Specular And Diffuse In Real Images](http://filmicgames.com/archives/233)", show how this can be done. The first image is the 'regular' appearance, and then (through image differencing) the diffuse-only and specular-only images. 

![Ordinary image of scissors](images/scissor-both.jpg)<br />
![Diffuse image of scissors](images/scissor-diff.jpg)<br />
![Specular image of scissors](images/scissor-spec.jpg)<br />

You can see this technique applied to a human face in [this video](https://www.youtube.com/watch?v=piJ4Zke7EUw) of the photoreal Digital Emily Project.

Incidentally, there are some [other very clever ways of separating specular from diffuse appearances](http://www.mit.edu/~yzli/ECCV02-Sep.pdf) of objects.


#### Transmissive Polarized Light: Visualizing Stress

Polarized light can also reveal internal stresses in (clear) materials, in a phenomenon known as [*photoelasticity*](https://en.wikipedia.org/wiki/Photoelasticity). Here's a plastic ruler between cross-polarized filters:

![Polarized light stress analysis](images/stress-anaylsis.jpg)<br />

![here's the setup](images/photoelasticity.jpg)<br />
Here's the setup to achive this. More information can be found at (e.g.) [Andrew Davidhazy's site](https://people.rit.edu/andpph/text-polarizer-by-glare.html). 

Some nice videos of polarization and stress visualization:
* [https://www.youtube.com/watch?v=3QBGgypAjkY](https://www.youtube.com/watch?v=3QBGgypAjkY)
* [https://www.youtube.com/watch?v=gP751qpm4n4](https://www.youtube.com/watch?v=gP751qpm4n4)
* [https://www.youtube.com/watch?v=7YaoSODkymc](https://www.youtube.com/watch?v=7YaoSODkymc)

---

### Schlieren Photography

Schlieren photography creates images which reveal, and depend on, minute differences in the index of refraction of air. In short, it depends not on a property of light, but on a property of light's medium. 

[Schlieren photography](https://www.youtube.com/watch?v=mLp_rSBzteI)

--- 
### Sonar and Ultrasound

It's well-known that bats and dolphins image the world through ultrasonic reflections. 

But were you aware of *human echolocation*? Here are three different individuals, who despite being blind are able to map a detailed mental plan of their surroundings:
* [Ben Underwood](https://www.youtube.com/watch?v=AiBeLoB6CKE)
* [Sam](https://www.youtube.com/watch?v=zXtExOMCDfE)
* [Daniel](https://www.youtube.com/watch?v=2IKT2akh0Ng)

Of course, there are also *devices* for sonar imaging. You are probably familiar with ultrasonic fetal imaging. 2D is more common, but recently 3D ultrasound has become available. 

![Fetal ultrasound](images/ultrasound.jpg)<br />

It has become popular in Japan to [3D-print copies of the unborn](http://microfabricator.com/articles/view/id/54cc021d313944ec4a8b456c/unborn-babies-come-to-life-through-new-full-color-ultrasound-3d-printing-service). 

![3D-printed fetus](images/3d-printed-unborn.jpg)<br />

Sonar can also be used to image *environments* in both 2D and 3D. Using equipment such as [this](http://www.blueview.com/products/3d-multibeam-scanning-sonar/3/), for example, people investigate and discover seafloor shipwrecks. 

![3D-printed fetus](images/sonar-shipwreck.jpg)<br />


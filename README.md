# qs-mgoqliksenseapps
Here are a range of Qlik Sense Apps to play with, edit and enjoy. All are built to work in [Qlik Sense 3.0](http://www.qlik.com/us/try-or-buy), and usually use a couple of Qlik Extensions from the [Qlik Branch](http://branch.qlik.com/).

I'll try and keep them themed with links to the necessary extension stated here in the readme.

## Exploring public domain image libraries
All where built to showcase my [MGO Image Grid v3 extension](https://github.com/murraygm/qse-mgoimagegrid).

### New York Public Library - public domain image dataset

**Grab from above or here's a direct link to the App [NY public library 3.qvf](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/NY%20public%20library%203.qvf)**

![NYPL 1](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/screenshots/nyplApp-00001.png) ![NYPL 2](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/screenshots/nyplApp-00002.png) ![NYPL 3](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/screenshots/nyplApp-00003.png)
This App uses version 3 of the MGO Image Grid extension to explore the NYPL's public domain image dataset of approx 190K images, with access to around 470K in total via their website/services. These are images that are free to download and use in your own work. Here's a link the the [NYPL.org site](https://www.nypl.org/) and to the [NYPL Labs Git repository](https://github.com/NYPL-publicdomain/data-and-utilities). Lots of great resources and utils on their GITHUB page.

The images themselves are served from NYPL.org so download speed and access may vary depending on the server response times.
The image grid view uses the lowest resolution image available from NYPL at 300px and the single image view uses the 760px version. If you follow the link on the single image you will be taken to the NYPL page where higher resolution versions may be available.

An image paging approach is used on the grid to help reduce the number of requests on the NYPL server and help with memory use in the App. It is customisable but please be aware that the more you load the larger the memory footprint. It is not advisable to use more than 100 images per image grid page.

A version of this app is also available with the MGO Image Grid project. 

### The British Libary - initial 1 million images released to Flickr

**Unfortunately it's too big to upload to GITHUB (100mb) so here's a dropbox link: [British Library.qvf](https://dl.dropboxusercontent.com/u/771748/British%20Library.qvf)**

![BRLIB 1](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/screenshots/BritLibApp-00001.png) ![BRLIB 2](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/screenshots/BritLibApp-00002.png)
In 2013 the British Library released 1million images via Flickr, as they put it: 
> "We have released over a million images onto Flickr Commons for anyone to use, remix and repurpose. These images were taken from the pages of 17th, 18th and 19th century books digitised by Microsoft who then generously gifted the scanned images to us, allowing us to release them back into the Public Domain."

The App uses version 3 of the MGO Image Grid extension to explore the images. The images themselves are served from from Flickr so download speed and access may vary depending on the server response times. The grid view uses the lowest resolution image available from Flickr and the single image view uses the large image version. It is not advisable to use more than 100 image items per page of a grid.

Find out more about the project here: [A million first steps](http://britishlibrary.typepad.co.uk/digital-scholarship/2013/12/a-million-first-steps.html)
Or get the data and assets on Git hub: [BL-Labs/imagedirectory](https://github.com/BL-Labs/imagedirectory)


### The Internet Archive - book images library

**Grab from above or here's a direct link to the App [Internet Archive Books with images.qvf](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/Internet%20Archive%20Books%20with%20images.qvf)**

![IA 1](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/screenshots/IntArchApp-00001.png) ![IA 2](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/screenshots/IntArchApp-00002.png) ![AI 3](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/screenshots/IntArchApp-00003.png) ![AI 4](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/screenshots/IntArchApp-00004.png) ![AI 5](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/screenshots/IntArchApp-00005.png)
The Internet Archive's Public Domain Book Images is a series of archives of images extracted from over 65K books. In total there are over 24 million scanned pages and over 5 million extracted images.
This App uses the list of books on the Internet Archive that you can browse the scanned pages of and that have the individual images extracted from the the pages as an archive of individual files. All available for download and use as in the public domain.

These books and images are taken from 1500-1922 and although many of the books are in non-latin characters all meta data is in Latin character set. This causes oddities and glitches as not unicode data assets. Due to the sheer volume of data, the extracted images are not being made available to browse through this app. Instead you can browse the cover thumbnail for each book, then browse the page thumbnails on a book by book basis. Also it's possible to see the extracted images via the Flickr link or by choosing to download the archive.
![AI 6](https://github.com/murraygm/qs-mgoqliksenseapps/raw/master/screenshots/IntArchApp-00006.png)

The App uses version 3 of the MGO Image Grid extension. The images themselves are served from archive.org so download speed and access may vary depending on the server response times.

All assets and data for this project can be found here on [archive.org](https://archive.org/details/bookimages)
and here's there GITHUB page: [internetarchive](https://github.com/internetarchive)



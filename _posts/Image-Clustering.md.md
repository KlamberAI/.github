# Image Clustering on Construction Foundation Site
The set of 14k+ images obtained from the Dataset: 
- Were clustered using Gaussian Process, 
- And a set of objectives are laid out to describe: how the image clustering process is segmented into non-usable and usable ones

Images that are found to be sensitive are:
(1). Documents
(2). Certificates
(3). People with a clarity on faces
(4). Text content that either discloses company name or a product
(5). Logos
(6). Accident Reports
(7). Personal photographs including family and all photographs in Personal folder

There are some images which have clarity on faces, which will be removed based on a face extractor or a person detector.

The proposals made based on this Dataset are:
- Drift Detection on Edge IoT Applications

I pitched these proposals to:
- Linux Foundation Events
- Other Intel Innovator Software Programme Published Events

A Technical Paper was proposed with: 
- Scirp JISP

For the Publication of:
- Improving Accuracy Through Age Drifting Scenarios of Faces

As a Technical Paper.

### Detailing the Image Clustering Process
Image-based Clustering is performed using `imgbeddings` library and then performing: Manifold based clustering. 

### Results of Image Clustering
![Cluster 2 - Work Site](https://live.staticflickr.com/65535/53049919748_4353836382_n.jpg)

![Cluster 3 - Machinery](https://live.staticflickr.com/65535/53049618444_0a004029c7_h.jpg)

![Cluster 6 - Cabins and Workable Areas](https://live.staticflickr.com/65535/53048847012_8fe20933ff_z.jpg)

![Cluster 9 - Machinery at Work Site](https://live.staticflickr.com/65535/53049426476_94908c4427_w.jpg)

![Cluster 12 - Some other Images at Site Refreshments](https://live.staticflickr.com/65535/53049425811_fe3af52714_n.jpg)

![Cluster 14 - Mechanical and Indicators](https://live.staticflickr.com/65535/53049919213_35277f8960_z.jpg)



> Written with [StackEdit](https://stackedit.io/).

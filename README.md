**www.openbiometrics.org**<br>
____
**About:** <br>

A communal biometrics framework supporting the development of open algorithms and reproducible evaluations.<br>

The catergories this open source deals with are: <br>
-Face Recognition <br>
-Age Estimation <br>
-Gender Estimation <br>
-Face Recognition Evaluation 
____

**Building and Installation**

1) Identify the latest stable [release tag](https://github.com/biometrics/openbr/releases) such as "v1.1.0"

2) Download all OpenBR source code and switch to that release tag:

    *$ git clone https://github.com/biometrics/openbr.git <br>
    $ cd openbr <br>
    $ git checkout <tag>   (eg: git checkout v1.1.0) <br>
    $ git submodule init <br>
    $ git submodule update <br>*
    
3) Build OpenBR by following the **[Build Instructions](http://openbiometrics.org/docs/install/)** for your OS.
____
**Getting Started:**
Here are the commands that allow users to utilize our many categories: <br>
1) *Face Recognition* <br>
$ br -algorithm FaceRecognition -compare me.jpg you.jpg

2) *Age Estimation* <br>
$ br -algorithm AgeEstimation -enroll me.jpg you.jpg metadata.csv

3) *Gender Estimation* <br>
$ br -algorithm GenderEstimation -enroll me.jpg you.jpg metadata.csv

4) *Face Recognition Evaluation* <br>
Accuracy on NIST MEDS Database, reproduce the results.
____
**Development:**

OpenBR is supported on Windows, Mac OS X, and Debian Linux. <br>
The project is licensed under Apache 2.0 and releases follow the Semantic Versioning convention. <br>
Internally the code base uses the CMake build system and requires Qt and OpenCV. <br>
____
**Support:**

Contact us at: <br>
openbr-dev@googlegroups.com

Need enterprise support? 
The OpenBR core development team offers custom algorithm development and sells an industry-leading facial recognition SDK through our company Rank One Computing.


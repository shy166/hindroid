# dsc180a Capstone project Part I: Hindroid Replication
Replicate [Hindroid](https://www.cse.ust.hk/~yqsong/papers/2017-KDD-HINDROID.pdf) Paper
timeline and task of dsc180a
## Part 0 The Data
The data for this project consists of
[apk](https://en.wikipedia.org/wiki/Android_application_package) files
(Android Application Packages), which are then decompiled to [Smali
Code](https://limbenjamin.com/articles/analysing-smali-code.html).

While portions focused on learning graph techniques will also use
examples from other languages (for example, python and java source code).
Under folder utils, building utility funtions to download apk and transfer apks smali code with python
- [x] APK downloading with xml files
- [x] APK -> Smali using apktool
### Example
make a downloading directory
```
cd ~/Downloads
mkdir apk
```
download apk from xml to certain directory
```
cd <repo directory>/utils
python
import utils
url = "https://apkpure.com/sitemaps/group.xml.gz" #example url
utils.download_apps(url, <path>)
```
decompile apk files from the directory to smali code
```
cd <repo directory>/utils
python
import utils
url = "https://apkpure.com/sitemaps/group.xml.gz" #example url
utils.download_apps(<apk file path>, <smali code output path>)
```
## Part 1
- [ ] Smali -> Graph Embedding & Feature Extraction with 
- [ ] ML
- [ ] Future Updates...

------------------------------------------------------------------------------------------------
## Prerequisite
- [ApkTool](https://ibotpeaches.github.io/Apktool/) to decompile an Anroid Apk to Smali code
- [networkX](https://networkx.github.io/documentation/stable/index.html)
to work and visualize graph structures. Install the package on your
## References

References are found both in the weekly readings, as well as in
[references](references.md). These will be update throughout the
quarter.



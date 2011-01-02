# Wow! Python Unzip (WowPyUnzip)

The project is mainly on extract **Chinese/Japsnse/Korean(CJK)** zip files.

In some linux distributions, such as Fedora/Ubuntu, there are few softwares can extract CJK filename correctly. I have tried `unzip`, `peazip` and `7z-zip`, but nothing helps.  In CJK communicity, many people suggest to patch `unzip` project with `unzpriv.h`. The method is hard for newbie, and the most important is even patched it still doesn't work.

That is why I develop myself tool, for easy, simple and correct. Try it, and have fun.


## Usage

1. Normal usage

        python unzip.py file.zip

2. Extract zip file with password

        python unzip.py -p password

3. Default encoding is Traditional Chinese(cp950). For Simplified Chinese(cp936), assign 'cp936' to '-e'

        python unzip.py -e cp936 -p password


## Required

- Python 2.6+



## Author

Yi-Feng, Tzeng (ant)

yftzeng _AT_ gmail.com


## License

MIT License


## Link

 [OpenFoundry](http://www.openfoundry.org/of/projects/1822/)

 [GitHub](git://github.com/yftzeng/WowPyUnzip.git)


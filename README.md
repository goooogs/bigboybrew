# bigboybrew
Homebrew Formulas for big boys

For sshpass: `brew install https://raw.githubusercontent.com/kadwanev/bigboybrew/master/Library/Formula/sshpass.rb`

#### Note
I have an error when installing sshpass with it expecting gsed rather than sed. To resolve:

    cd /usr/local/Library/ENV/4.3
    ln -s /usr/local/bin/gsed gsed


`brew create --force http://sourceforge.net/projects/sshpass/files/sshpass/1.06/sshpass-1.06.tar.gz`
`brew install sshpass`


```bash
./configure --disable-debug --disable-dependency-tracking --disable-silent-rules --prefix=/usr/local/Cellar/sshpass/1.06

make

make install
```

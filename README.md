# Debian GNU/Linux

**Base**

    sudo apt update
    sudo apt upgrade -y
    sudo apt install -y apt-transport-https curl gnupg secure-delete wget

**Development**

    sudo apt install -y build-essential git nasm vim

**Java**

    sudo apt install -y openjdk-11-jdk openjdk-17-jdk

Java 8: [Amazon Corretto](https://docs.aws.amazon.com/corretto/latest/corretto-8-ug/generic-linux-install.html)

**Python**

    sudo apt install -y pipenv python3-pip python3-pygments

**Graphics**

    sudo apt install -y inkscape libavcodec-extra

**TeX Live**

    sudo apt install -y \
        texlive-bibtex-extra \
        texlive-fonts-extra \
        texlive-lang-spanish \
        texlive-latex-recommended \
        texlive-luatex \
        texlive-pictures \
        texlive-science \
        biber

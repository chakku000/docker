FROM paperist/alpine-texlive-ja
RUN wget https://raw.githubusercontent.com/chakku000/dotfiles/master/.latexmkrc -P $HOME
RUN wget --trust-server-name "https://ja.osdn.net/projects/mytexpert/downloads/26068/jlisting.sty.bz2/" && bunzip2 jlisting.sty.bz2 && cp jlisting.sty /usr/local/texlive/2018/texmf-dist/tex/latex/listing && chmod 644 /usr/local/texlive/2018/texmf-dist/tex/latex/listing/jlisting.sty && mktexlsr
CMD /bin/bash

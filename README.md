# APT patch for Lucid (10.04)
  - rm -rf /etc/apt/sources.list && wget -O /etc/apt/sources.list https://raw.githubusercontent.com/glowiak/ubuntu-tools/master/lucid-src.lst
  - or if you don't have wget:
  - rm -rf /etc/apt/sources.list && curl -L -o /etc/apt/sources.list https://raw.githubusercontent.com/glowiak/ubuntu-tools/master/lucid-src.lst

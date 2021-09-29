# BoF_Bedrock
![Bedrock](/logo.png)
# BoF_Bedrock First install
1. Termux in Google Play
2. pkg install proot-distro
3. proot-distro install debian 
4. proot-distro login debian
5. apt update && apt upgrade -y
6. apt install git
7. apt install wget
8. wget http://ftp.br.debian.org/debian/pool/main/libj/libjpeg-turbo/libjpeg62-turbo_2.0.6-4_arm64.deb
9. wget http://ftp.br.debian.org/debian/pool/main/o/openjdk-16/openjdk-16-jre-headless_16.0.2+7-2_arm64.deb
10. wget http://ftp.br.debian.org/debian/pool/main/o/openjdk-16/openjdk-16-jdk-headless_16.0.2+7-2_arm64.deb
11. apt install -y ./libjpeg62-turbo_2.0.6-4_arm64.deb
12. apt install -y ./openjdk-16-jre-headless_16.0.2+7-2_arm64.deb
13. apt install -y ./openjdk-16-jdk-headless_16.0.2+7-2_arm64.deb
14. git clone https://github.com/g0dm0d/BoF_Bedrock
15. cd BoF_Bedrock
16. java -Xmx512m -jar Geyser.jar nogui
# BoF_Bedrock next run
1. proot-distro login debian
2. cd BoF_Bedrock
3. java -Xmx512m -jar Geyser.jar nogui

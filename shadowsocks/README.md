0、move this dir to remote at ~/
1、docker build -t ssserver .
2、docker run -i -t -d -p 9000:9000 -p 9001:9001 -p 9002:9002 -p 9003:9003 -p 9004:9004 -v ~/shadowsocks/config.json:/config.json --name ss ssserver /server
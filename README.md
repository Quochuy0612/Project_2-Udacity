./create.sh UdagramIAM infrastructure/udagram-iam.yaml infrastructure/parameters/udagram-iam.json

./create.sh UdagramWAF infrastructure/udagram-waf.yaml infrastructure/parameters/udagram-waf.json

./create.sh UdagramS3 infrastructure/udagram-s3.yaml infrastructure/parameters/udagram-s3.json

./create.sh UdagramNetwork infrastructure/udagram-network.yaml infrastructure/parameters/udagram-network.json

./create.sh UdagramBastion infrastructure/udagram-server01.yaml infrastructure/parameters/udagram-server01.json

./create.sh UdagramEC2 infrastructure/udagram-server02.yaml infrastructure/parameters/udagram-server02.json
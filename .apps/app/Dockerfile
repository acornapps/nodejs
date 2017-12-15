FROM node:carbon
MAINTAINER acornsoft <apps@acornsoft.com>
# 앱 디렉토리 생성
WORKDIR /usr/src/app

# 앱 의존성 설치
COPY package*.json ./
RUN npm install

# 앱 소스 추가
COPY . .

EXPOSE 8080
CMD [ "npm", "start" ]


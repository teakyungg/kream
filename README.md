# Kream
## git clone 후 npm i 설정 필수
GitHub에 node_modules를 업로드하면 용량이 불필요하게 커지고,  
npm i를 실행하면 package.json과 package-lock.json을 기반으로 필요한 패키지를 자동으로 설치할 수 있다.  
따라서 새로운 프로젝트에는 node_modules가 포함되지 않으며,  
npm i를 실행하여 package-lock.json의 devDependencies 목록을 참고해 패키지를 설치하는 과정이 필요하다.  
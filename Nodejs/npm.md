# Ubuntu 환경에서 npm 설치, 업데이트 학;

> Ubuntu에서 첫 npm 설치 시 낮은 버전의 npm이 설치되어 오류가 발생하는 경우가 있습니다. 이에 대한 해결방법입니다.

1. ubuntu 환경에서 npm, yarn 사용을 위한 개발환경 설정

    ```
    $ sudo apt install npm
    ```

    5. ubuntu 환경에서 npm, yarn 사용을 위한 개발환경 설정
        - ubuntu 16.04 환경에서 apt install npm을 실행하면 이전 npm 버전이 설치되어 오류가 발생합니다. 따라서 아래와 같은 과정을 통해 npm을 업데이트 해줍니다.
        - n 은 node.js 버전관리 플러그인입니다.
        ```
        $ sudo apt install npm
        $ npm -v
        $ sudo npm install -g n
        ```

        1. sudo n lts
            - n latest (최신 버전)
            - n stable (안정화 버전)
            - n lts (lts 버전)
                ```
                $ sudo n lts
                $ npm -v
                ```

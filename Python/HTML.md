## Url
###Url
> 애플리케이션이 리소스에 접근할 수 있는 방법

### Url의 구조
> Protocol + SubDomain + Domain + Slug + Article Permalink

1. protocol의 종류 : http(웹 서버에 접속), ftp(파일 서버에 접속), telnet(원격지 접속), malito(전자메일 서버에 접속)
2. com, net 등등 : TLD(top level domain, DNS에 쓰인다)
3. '/' : 파일 경로
4. '?' : 파라미터
5. '#' : 프레그먼트
---
## HTML
> 웹 페이지를 위한 마크업 언어
```html
<!doctype html>

<html>
    <head>
        <title>
            HTML의 기본적인 문법
        </title>
    </head>
    <body>
        <h1> 제목 1 </h1>
        <h2> 제목 2 </h2>
        <h3> 제목 3 </h3>
        
        <!-- 문서를 분할하는 태그 div -->
        <div>
            div
        </div>
        
        <!-- 단락을 구분하는 대크 p (기본 마진 존재) -->
        <p>
            p
        </p>
        
        <!-- 한 줄을 감싸는 태그 span -->
        <span>
            span
        </span>
        엔터<br>
        <a href="https://naver.com target="_blank"> 링크 </a><br>
        <img src="http://blogfiles.naver.net/20151021_61/gonggamcom_14454090756396FPUJ_JPEG/%C4%B8%C3%B3.JPG"><br>
        <video src="" autoplay controls></video><br>
        
        <!-- 테이블 -->
        <table>
            <tr>
                <td> 테이블 </td>
                <td> 테이블 </td>
                <td> 테이블 </td>
            </tr>
            <tr>
                <td> 테이블 </td>
                <td> 테이블 </td>
                <td> 테이블 </td>
            </tr>
            <tr>
                <td> 테이블 </td>
                <td> 테이블 </td>
                <td> 테이블 </td>
            </tr>
        </table>
        
        <!-- 순서가 있는 리스트 -->
        <ol>
            <li>첫 번째</li>
            <li>두 번째</li>
            <li>세 번째</li>
        </ol>
        
        <!-- 순서가 없는 리스트 -->
        <ul>
            <li>첫 번째</li>
            <li>두 번째</li>
            <li>세 번째</li>
        </ul>
    </body>
</html>
```

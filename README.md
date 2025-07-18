# skcc-aikms-ra-public-repo

이 리파지토리의 목적은 AIKMS에 등록되는 Repository의 README에 올릴 이미지 파일을 퍼블리싱하기 위한 용도입니다.

skccmygit의 리파지토리는 internal이기 때문에 README에 직접 이미지를 삽입할 경우, AIKMS에서는 해당 REAME에 종속된 이미지 파일을 브라우저에 로딩할 수 없습니다.
따라서, 이미지 파일은 public으로 만들어진 이 리파지토리에 올리면 됩니다.

## 이미지 파일 처리 방법
1. 현재 리파지토리에 이미지를 올릴 신규 폴더를 생성한다.  (폴더 이름은 자신의 리파지토리 이름과 동일하게)
2. 해당 폴더에 본인의 리파지토리 들어있던 이미지 파일을 복업로드한다.
3. 본인의 리파지토리 Readme 파일에 있던 이미지 링크를 다음과 같이 수정한다.

- 변경전 : ```<img src="./common-list.png" width="400"/>```
  
- 변경후 : ```<img src="https://raw.githubusercontent.com/skccmygit/skcc-aikms-ra-public-repo/refs/heads/main/ra-front-vue-ui-components/common-list.png" width="400"/>```
   
* 위에서 보듯이 ```"https://raw.githubusercontent.com/skccmygit/skcc-aikms-ra-public-repo/refs/heads/main" + "/폴더이름/이미지파일명"```과 같이 만들어 주는 게 핵심

<hr />

<h3> 예시 </h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/skccmygit/skcc-aikms-ra-public-repo/refs/heads/main/ra-front-vue-ui-components/common-list.png" width="800"/>
</p>

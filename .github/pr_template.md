### Description[^guide]
<!-- 작업에 대한 설명을 입력하고, 작업에 대해 잘 모르는 사람도 알 수 있도록 충분한 Context를 작성합니다 -->

#### 🤔 Concern Point
<!-- (Optional) 혹시 마음에 걸리는 부분이 있거나 조언을 얻고 싶은 부분이 있는 경우 입력합니다 -->

#### 📸 Screenshot/GIF
<!-- (Optional) Figma/데모 페이지에서 충분한 동작이 보이지 않는 경우 Screenshot을 추가합니다 (ex. 기존 디자인이 Figma에 없음, 인터렉션에 대한 업데이트, ...)-->

|AS-IS|TO-BE|
|-----|-----|
|image|image|

#### ✅ CheckList
<!-- (Optional) 테스트가 필요한 경우 테스트 방법을 추가하여 체크리스트를 제공합니다 -->

### Links
<!-- PR에서 같이 보면 좋은 참고할 링크(기획, 디자인 시안, JIRA 등)를 추가합니다 -->

<!-- 
## PR & Code Review Process ##
1. `main` 브랜치로 직접 변경사항을 만들지 않고, Pull Request를 만들어 반영합니다.
2. Commit이 Test, Lint, Preview Deploy등의 CI를 통과하지 못하는 경우, 일단 CI를 통과하도록 합니다.
3. 2명 이상의 Web FrontEnd 개발자의 코드리뷰 이후, 승인을 받으면 `main`으로 머지합니다. 
-->

[^guide]: <details><summary>Description 가이드</summary>
    
    - 기획서/디자인에는 있지만 PR에서는 구현되지 않은 부분이 있다면 충분한 설명을 남깁니다.  
      - [Good👍]  
        - Popup Header 구현  
        - 피그마에 있는 Tab 컴포넌트는 작업되지 않았고 ~하게 구현될 예정입니다. 
      - [Bad👎]  
        - Popup Header 구현  
    - 의미있는 정보를 담은 변경사항을 적습니다  
      - [Good👍]   
        1. Button 컴포넌트 `label` property 추가  
        2. Button 컴포넌트 스타일 변경 (as-is, to-be 이미지 추가)  
        3. [Breaking Changes] Button 컴포넌트 `height` prop 제거  
      - [Bad👎]  
        - Button 컴포넌트 업데이트  

</details>

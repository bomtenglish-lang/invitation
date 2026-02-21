# 유정민 돌잔치 초대장

모바일 친화적인 돌잔치 초대장 웹페이지입니다.

## 사용 방법

1. **메인 사진 넣기**  
   `images` 폴더에 사용하실 사진을 `main.jpg` 로 저장해 주세요.  
   (원본 파일명: `9963195_정진영님_100일 2차 (5).jpg` 를 복사 후 `main.jpg` 로 저장하시면 됩니다.)

2. **GitHub에 올리기**
   ```bash
   git init
   git add .
   git commit -m "돌잔치 초대장"
   git branch -M main
   git remote add origin https://github.com/본인아이디/저장소이름.git
   git push -u origin main
   ```

3. **Vercel로 배포**
   - [vercel.com](https://vercel.com) 에서 GitHub 로그인 후 이 저장소 연결
   - 프로젝트 선택 후 Deploy (별도 설정 없이 배포 가능)

4. **미리보기 문구 (카카오톡/메신저)**  
   배포된 주소(예: `https://dolparty-xxx.vercel.app`)를 지인에게 보내면  
   **"26년 4월 25일 토요일, 유정민의 돌잔치에 초대합니다!"** 문구와 메인 사진이 미리보기로 보입니다.

   - 카카오톡에서 미리보기가 안 바뀌면: [카카오 캐시 초기화](https://developers.kakao.com/tool/clear/og) 에서 해당 URL 입력 후 초기화하면 됩니다.
   - 배포 후 `index.html` 안의 `og:image` 를 **절대 URL**로 바꾸면 더 안정적입니다.  
     예: `content="https://당신도메인.vercel.app/images/main.jpg"`

## 포함된 정보

- **일시**: 26년 4월 25일 토요일 11시 30분  
- **장소**: 더퍼스트클래스파티 강서NH서울타워점, 파티홀 ([네이버 지도](https://naver.me/5ss0AH07))  
- **아버지**: 유승범 · **어머니**: 정진영  

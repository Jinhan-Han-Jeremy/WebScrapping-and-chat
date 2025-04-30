# WebScrapping-and-chat

## 스프링 부트 자바
### auth-controller
POST
/auth/refresh

### kakao-auth-controller
POST
/auth/kakao/logout

GET
/auth/kakao/unlink

GET
/auth/kakao/login

GET
/auth/kakao/frontCallback

GET
/auth/kakao/callback

### chat-api-controller
POST
/app/rooms/{roomId}/enter

PATCH
/app/rooms/{roomId}/nickname.update

PATCH
/app/rooms/{roomId}/left

GET
/app/rooms/{roomId}/message.more

GET
/app/rooms/my

### chat-controller
POST
/api/chat/rooms

### user-controller
PATCH
/auth/user/update

PATCH
/auth/user/delete

GET
/auth/user/me

### trending-controller
GET
/api/v1/trending/keywords

GET
/api/v1/trending/keywords/ranking/weekly

GET
/api/v1/trending/keywords/ranking/realtime

GET
/api/v1/trending/keywords/ranking/monthly

GET
/api/v1/trending/keywords/ranking/daily

## FastAPI
GET
/api/v1/keywords-rank/top

GET
/api/v1/keywords-rank/bottom

GET
/api/v1/last-keywords-rank/top

GET
/api/v1/last-keywords-rank/bottom

GET
/api/v1/google-rank/top

GET
/api/v1/google-rank/bottom


GET
/api/v1/last-google-rank/top

GET
/api/v1/last-google-rank/bottom

기획 : 
https://sprout-shallot-70b.notion.site/1-Trendly-19009a18538e80bcbc55f33b8f8e9b8a

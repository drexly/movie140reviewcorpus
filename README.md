# movie140reviewcorpus
네이버 영화 164397건 중 140자 평이 있는 영화별 평점 raw data for spark

## Database Scheme

* 파일명: 영화 고유 ID Primary key-해당 영화 장르 분류(zero or more, splitted by ',').txt

* 파일 내용(one or more): (영화 고유 ID,댓글 ID Primary key,평점(int 0-10),공감수,비공감수,'한국어 댓글 내용')

====온라인 쇼핑몰 프로젝트의 API 명세서를 직접 설계하기=====
-회원 기능
    • 회원 등록
        HTTP Method : POST
        URI : /members
        
    • 회원 목록 조회
        HTTP Method : GET
        URI : /members

    • 개별 회원 정보 상세 조회
        HTTP Method : GET
        URI : /members/{number}
    
    • 회원 정보 수정
        HTTP Method : PATCH
        URI : /members/{number}
        
    • 회원 삭제
        HTTP Method : DELETE
        URI : /members/{number}

-상품 기능
    • 상품 정보 등록
        HTTP Method : POST
        URI : /object

    • 상품 목록 조회
        HTTP Method : GET
        URI : /object

    • 개별 상품 정보 상세 조회
        HTTP Method : GET
        URI : /object/{number}

    • 상품 정보 수정
        HTTP Method : PATCH
        URI : /object/{number}

    • 상품 삭제
        HTTP Method : DELETE
        URI : /object/{number}

-주문 기능
    • 주문 정보 생성
        HTTP Method : POST
        URI : /order

    • 주문 목록 조회
        HTTP Method : GET
        URI : /order

    • 개별 주문 정보 상세 조회
        HTTP Method : GET
        URI : /order/{number}

    • 주문 취소
        HTTP Method : DELETE
        URI : /order{number}



====강의 내용을 요약 정리하기====

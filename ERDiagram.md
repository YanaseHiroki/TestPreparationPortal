users
    userId
        password
        displaySetting
        levels
            testeeExp: int
            menterExp: int
chatRooms
    chatRoomId
        postId
            poster: str
            kind: str(text / report / response / suggest)
            comment: str(
                "you did it" / 
                "did: achievement: int %, what: str" / 
                "suggestTarget: int, what: str"
            )


         
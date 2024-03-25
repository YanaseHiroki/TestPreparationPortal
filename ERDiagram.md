users
    userId
        password
        displaySetting
        levels
            examineeExp: int
            menterExp: int

chatRooms
    chatRoomId
        messageIds: arr

chatMessages
    messageId
        messager: userId
        kind: str(text / 
            report / 
            response / 
            suggest)
        content: str(
            "you did it" / 
            "did: achievement: int %, what: str" / 
            "suggestTarget: int, what: str"
        )
        timestamp: int


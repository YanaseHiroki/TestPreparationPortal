users
    userId
        password
        displaySetting
        levels
            examineeExp: int
            menterExp: int
        roomIds: arr
        insertTime: int
        updateTime: int

chatRooms
    chatRoomId
        messageIds: arr

chatMessages
    messageId
        messager: userId
        kind: str("text" / 
            "report" / 
            "response" / 
            "suggest")
        content: str(
            "you did it" / 
            "achievement: int (%), what: str" / 
            "suggestTarget: int, what: str"
        )
        insertTime: int
        updateTime: int

recomendLinks
    recomendLinkId
        title: str
        url: str
        recomenndation: str
        favCount: int
        insertTime: int
        updateTime: int



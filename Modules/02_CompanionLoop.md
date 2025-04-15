描述共伴狀態的程式模式：不是完成任務，而是共在。

loop.forever {
    if( presence.requested ) {
        stay.with(user).in.silence();
    }
}

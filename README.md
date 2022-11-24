# SwiftUI_Menu_WithButton

```swift
          Menu {
                                CustomButton {
                                    FeedbackGenerator.impact()
                                    // Do Something
                                    withAnimation {
                                        self.vm.selectingMode = true
                                    }
                                } content: {
                                    HStack(spacing: adaptiveSpacing(base: .width, 0)) {
                                        Image(systemName: "music.note.house")
                                            .adaptiveFontSize(16)
                                            .foregroundColor(Color(red: 230/255, green: 230/255, blue: 230/255))
                                        Text("기본 믹스 변경하기")
                                            .fontWeight(.medium)
                                            .adaptiveFontSize(16)
                                            .foregroundColor(Color(red: 230/255, green: 230/255, blue: 230/255))
                                    }
                                }
                                
                            } label: {
                                Rectangle()
                                    .opacity(0)
                            }
                                .buttonStyle(PlainButtonStyle())
```

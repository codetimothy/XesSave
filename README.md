# XesSave
保护你的学而思!

它可以关掉学而思的拦截器，可以防刷赞也可以屏蔽那些不良信息。
当然没凌锋的[XesExt](https://github.com/FurryR/XesExt)好。   
这里用了三个检测器来看是否有刷赞代码。

```javascript
const likeevent = document.querySelector('.like')
    if (likeevent) {
      likeevent.click = () => {
        console.alert('XesSave检测到点赞按钮被触发。')
      }
    }
    const fasevent = document.querySelector('.favorites')
    if (fasevent) {
      fasevent.click = () => {
        console.alert('XesSave检测到收藏按钮被触发。')
      }
    }
    const followevent = document.querySelector('.focus-btn')
    if (followbtn) {
    followbtn.click = () => {
        console.alert('XesExt 检测到关注按钮被触发。')
      }
    }
```

我的第一个程序，做的肯定不大好。

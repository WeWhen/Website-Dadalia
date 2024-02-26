<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="../图片/dali.jpg"/>
    <link rel="stylesheet" href="../css通用样式表.css"> 
    <link rel="stylesheet" href="../主页样式表.css">
    <title>达达利亚(　o=^•ェ•)つロ干杯！</title>
</head>
<body>
    <header>    
    啦啦啦啦啦
            <div class="header-logo-container">
                <a href="主页.html">
                    <img id="logo" src="../图片/logo.png" alt="网页logo" height="60px">
                </a>
                <a class="toggle-nav">
                    <img id="director" src="../图片/director.png" alt="导航栏" height="50px">
                </a>
            </div>
            <div class="search-box">
                <input type="text" placeholder="搜索">
                <button type="submit">搜索</button>
            </div>
            <div class="header-logotext-container">
            <a href="主页.html"><img src="../图片/ajax.png" height="60px"></a>
            </div>
    </header>
    <button id="showLoginPopupBtn">下滑页面去登录</button>
    <div id="loginPopup" class="container-login">
        <button class="close-login" onclick="closeLoginPopup()">×</button>
        <div class="form-box">
            <!-- 注册 -->
            <div class="register-box hidden">
                <h1>register</h1>
                <input type="text" placeholder="用户名">
                <input type="email" placeholder="邮箱">
                <input type="password" placeholder="密码">
                <input type="password" placeholder="确认密码">
                <button>注册</button>
            </div>
            <!-- 登录 -->
            <div class="login-box">
                <h1>login</h1>
                <input type="text" placeholder="用户名">
                <input type="password" placeholder="密码">
                <button>登录</button>
            </div>
        </div>
        <div class="con-box left">
            <h2>欢迎来到<span>达达利亚</span></h2>
            <img src="../图片/图片素材/原神素材 (28).webp" alt="">
            <p>已有账号</p>
            <button id="login">去登录</button>
        </div>
        <div class="con-box right">
            <h2>欢迎来到<span>达达利亚</span></h2>
            <img src="../图片/图片素材/原神素材 (29).webp" alt="">
            <p>没有账号？</p>
            <button id="register">去注册</button>
        </div>
    </div>
    <div class="sidebar">
        <button class="close-nav">关闭</button>
        <div class="header-image-container">
            <a href="主页.html">
             <img src="../图片/dali.jpg" alt="小达达利亚"> 
            </a>
        </div>
        <nav class="side-director">   
        <a href="主页.html">首页</a>
        <a href="博客.html">博客</a>
        <a href="日记.html">日记</a>
        <a href="视频.html">视频</a>
        <a href="摄影.html">摄影</a>
        <a href="技术.html">技术</a>
        <a href="阅读清单.html">阅读清单</a>
        <a href="关于我.html">关于</a>
        </nav>
    </div>
    <nav class="header-director">
        <a href="主页.html">首页</a>
        <a href="博客.html">博客</a>
        <a href="日记.html">日记</a>
        <a href="视频.html">视频</a>
        <a href="摄影.html">摄影</a>
        <a href="技术.html">技术</a>
        <a href="阅读清单.html">阅读清单</a>
        <a href="关于我.html">关于</a>
    </nav>

    <div class="container-main">
                <div class="carousel-container">
                    <div class="carousel-track">
                        <div class="carousel-item">
                            <a href="链接2.html">
                                <img src="../图片/图片素材/原神壁纸 (1).jpg" alt="轮播图2">
                            </a>
                        </div>
                        <div class="carousel-item">
                            <a href="链接2.html">
                                <img src="../图片/图片素材/原神壁纸 (2).jpg" alt="轮播图2">
                            </a>
                        </div>
                        <div class="carousel-item">
                            <a href="链接2.html">
                                <img src="../图片/图片素材/原神壁纸 (3).jpg" alt="轮播图2">
                            </a>
                        </div>
                        <div class="carousel-item">
                            <a href="链接1.html">
                                <img src="../图片/图片素材/原神壁纸 (4).jpg" alt="轮播图1">
                            </a>
                        </div>
                        <div class="carousel-item">
                            <a href="链接2.html">
                                <img src="../图片/图片素材/原神壁纸 (5).jpg" alt="轮播图2">
                            </a>
                        </div>
                    </div>
                    <button class="carousel-button prev" onclick="prevSlide()">❮</button>
                    <button class="carousel-button next" onclick="nextSlide()">❯</button>
                </div>

        <div class="right-links">
            <div class="row">
                <div class="small-link">
                    <img src="../图片/图片素材/原神壁纸 (1).jpg" alt="Small Link 1">
                    <h3>小窗口标题1</h3>
                </div>
                <div class="small-link">
                    <img src="../图片/图片素材/原神壁纸 (2).jpg" alt="Small Link 2">  
                    <h3>小窗口标题2</h3>
                </div>
                <div class="small-link">
                    <img src="../图片/图片素材/原神壁纸 (3).jpg" alt="Small Link 3">
                    <h3>小窗口标题3</h3>
                </div>
            </div>

            <div class="row">
                <div class="small-link">
                    <img src="../图片/图片素材/原神壁纸 (4).jpg" alt="Small Link 4">
                    <h3>小窗口标题4</h3>
                </div>
                <div class="small-link">
                    <img src="../图片/图片素材/原神壁纸 (5).jpg" alt="Small Link 5">
                    <h3>小窗口标题5</h3>
                </div>
                <div class="small-link">
                    <img src="../图片/图片素材/原神壁纸 (6).jpg" alt="Small Link 6">
                    <h3>小窗口标题6</h3>
                </div>
            </div>
        </div>
    </div>
<div class="container-other">
    <div class="divider"></div>
    <!-- 日记，摄影 -->
    <div class="row">
        <div class="small-link">
            <img src="../图片/图片素材/原神素材 (1).webp" alt="Small Link 6">
            <h3>小窗口标题6</h3>
        </div>
        <div class="small-link">
            <img src="../图片/图片素材/原神素材 (2).webp" alt="Small Link 6">
            <h3>小窗口标题6</h3>
        </div>
        <div class="small-link">
            <img src="../图片/图片素材/原神素材 (3).webp" alt="Small Link 6">
            <h3>小窗口标题6</h3>
        </div>
        <div class="small-link">
            <img src="../图片/图片素材/原神素材 (4).webp" alt="Small Link 6">
            <h3>小窗口标题6</h3>
        </div>
        <div class="small-link">
            <img src="../图片/图片素材/原神素材 (5).webp" alt="Small Link 6">
            <h3>小窗口标题6</h3>
        </div>
    </div>
    </div>
    <div class="contanier-tech">
    <div class="divider"></div>
    <!-- 技术 -->
    <div class="row">
        <div class="small-link">
            <img src="../图片/图片素材/原神素材 (6).webp" alt="Small Link 6">
            <h3>小窗口标题6</h3>
        </div>
        <div class="small-link">
            <img src="../图片/图片素材/原神素材 (7).webp" alt="Small Link 6">
            <h3>小窗口标题6</h3>
        </div>
        <div class="small-link">
            <img src="../图片/图片素材/原神素材 (8).webp" alt="Small Link 6">
            <h3>小窗口标题6</h3>
        </div>
        <div class="small-link">
            <img src="../图片/图片素材/原神素材 (9).webp" alt="Small Link 6">
            <h3>小窗口标题6</h3>
        </div>
        <div class="small-link">
            <img src="../图片/图片素材/原神素材 (10).webp" alt="Small Link 6">
            <h3>小窗口标题6</h3>
        </div>
    </div>
</div>
    <button id="changeThemeBtn">更改主题</button>
 
<script src="../js事件响应.js"></script>
<script>
    // 要操作到的元素
    let login=document.getElementById('login');
    let register=document.getElementById('register');
    let form_box=document.getElementsByClassName('form-box')[0];
    let register_box=document.getElementsByClassName('register-box')[0];
    let login_box=document.getElementsByClassName('login-box')[0];
    // 去注册按钮点击事件
    register.addEventListener('click',()=>{
        form_box.style.transform='translateX(80%)';
        login_box.classList.add('hidden');
        register_box.classList.remove('hidden');
    })
    // 去登录按钮点击事件
    login.addEventListener('click',()=>{
        form_box.style.transform='translateX(0%)';
        register_box.classList.add('hidden');
        login_box.classList.remove('hidden');
    })
</script>
<script>
    // 主页轮播图
    let carouselIndex = 0;
    const items = document.querySelectorAll('.carousel-item');
    const totalItems = items.length;

    function nextSlide() {
        if (carouselIndex < totalItems - 1) {
            carouselIndex++;
        } else {
            carouselIndex = 0;
        }
        console.log("fhusif")
        updateCarousel();
    }

    function prevSlide() {
        if (carouselIndex > 0) {
            carouselIndex--;
        } else {
            carouselIndex = totalItems - 1;
        }
        
        console.log("fhudsafsjkif")
        updateCarousel();
    }

    function updateCarousel() {
        const newTransformValue = -carouselIndex * 100 + '%';
        document.querySelector('.carousel-track').style.transform = 'translateX(' + newTransformValue + ')';
    }

    // 设置定时器，每隔3000毫秒（3秒）切换到下一个轮播项
    setInterval(function () {
        nextSlide();
    }, 3000);

    // 在页面加载完成时显示登录弹窗
window.onload = function () {
    showLoginPopup();
};
    // 显示登录弹窗
function showLoginPopup() {
    document.getElementById('loginPopup').style.display = 'block';
}

// 关闭登录弹窗
function closeLoginPopup() {
    document.getElementById('loginPopup').style.display = 'none';
}

// 登录或注册逻辑
function loginOrRegister() {
    // 从表单获取用户名和密码
    var username = document.getElementById('username').value;
    var password = document.getElementById('password').value;

    // 在这里执行登录或注册逻辑
    // 为简单起见，我们只是将信息记录到控制台
    console.log('用户名：' + username);
    console.log('密码：' + password);

    // 你可以在这里添加与服务器通信的 AJAX 请求，用于处理登录/注册
    // 例如，使用 fetch API 或 jQuery.ajax
}

</script>
</body>
</html>

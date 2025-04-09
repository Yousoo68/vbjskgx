<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>섹시유수 썰 비번 모음</title>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <link rel="apple-touch-icon" sizes="180x180" href="https://raw.githubusercontent.com/Yousoo68/photo/refs/heads/main/Secret.jpeg">
    <link rel="manifest" href="manifest.json">
    <style>
        :root {
            --primary: #6a5acd;
            --secondary: #483d8b;
            --light: #f8f9fa;
            --dark: #343a40;
            --success: #28a745;
            --error: #dc3545;
            --radius: 10px;
            --shadow: 0 6px 15px rgba(0,0,0,0.1);
            --transition: all 0.3s ease;
        }
        body {
            font-family: 'Segoe UI', system-ui, sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            min-height: 100vh;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            color: var(--dark);
        }
        .container {
            background: white;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            width: 100%;
            max-width: 600px;
            padding: 30px;
            margin-top: 20px;
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.5s, transform 0.5s;
        }
        .show {
            opacity: 1;
            transform: translateY(0);
        }
        h1 {
            color: var(--primary);
            margin-bottom: 5px;
            text-align: center;
        }
        .subtitle {
            color: #6c757d;
            text-align: center;
            margin-bottom: 25px;
            font-size: 0.9em;
        }
        .password-item {
            background: #f8f9fa;
            border-radius: var(--radius);
            padding: 15px;
            margin-bottom: 15px;
            cursor: pointer;
            transition: var(--transition);
            border-left: 4px solid var(--primary);
            position: relative;
            overflow: hidden;
        }
        .password-item:hover {
            transform: translateY(-3px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .password-item:active {
            transform: translateY(0);
        }
        .password-item .title {
            font-weight: 600;
            margin-bottom: 5px;
            color: var(--primary);
        }
        .password-item .password {
            font-family: 'Courier New', monospace;
            word-break: break-all;
            font-size: 14px;
            color: var(--dark);
        }
        .auth-container {
            width: 100%;
            max-width: 400px;
            background: white;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            padding: 25px;
            margin-bottom: 20px;
        }
        .btn {
            background: var(--primary);
            color: white;
            border: none;
            padding: 12px;
            border-radius: var(--radius);
            width: 100%;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 10px;
        }
        .btn:hover {
            background: var(--secondary);
        }
        .btn-google {
            background: #4285F4;
        }
        .btn-google:hover {
            background: #357ABD;
        }
        .user-info {
            position: fixed;
            bottom: 20px;
            background: white;
            padding: 10px 15px;
            border-radius: 30px;
            box-shadow: var(--shadow);
            display: flex;
            align-items: center;
            font-size: 14px;
        }
        .logout-btn {
            margin-left: 10px;
            background: var(--error);
            color: white;
            border: none;
            border-radius: 4px;
            padding: 5px 10px;
            cursor: pointer;
            font-size: 12px;
        }
        .admin-panel {
            margin-top: 20px;
            padding: 15px;
            background: #f1f1f1;
            border-radius: var(--radius);
        }
        .toggle-container {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }
        .toggle-switch {
            position: relative;
            display: inline-block;
            width: 50px;
            height: 24px;
            margin-right: 10px;
        }
        .toggle-switch input {
            opacity: 0;
            width: 0;
            height: 0;
        }
        .slider {
            position: absolute;
            cursor: pointer;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: #ccc;
            transition: .4s;
            border-radius: 24px;
        }
        .slider:before {
            position: absolute;
            content: "";
            height: 16px;
            width: 16px;
            left: 4px;
            bottom: 4px;
            background-color: white;
            transition: .4s;
            border-radius: 50%;
        }
        input:checked + .slider {
            background-color: var(--primary);
        }
        input:checked + .slider:before {
            transform: translateX(26px);
        }
    </style>
</head>
<body>
    <div class="auth-container" id="auth-container">
        <button id="google-login-btn" class="btn btn-google">
            Google로 로그인
        </button>
    </div>

    <div class="container" id="content-container">
        <h1>섹시유수 썰 비번 모음</h1>
        <div class="subtitle">(썰 이름을 클릭하면 복사할 수 있습니다)</div>
        
        <div class="password-item" data-id="1">
            <div class="title">공섹썰🌶 비번</div>
            <div class="password">TzrsPMPuP9MD3LjTyhvh2flA14wk1e1p9PgUWg2a0JuHd4NGhMOkDBxT1pEPllb68ZIntbExsn3Wt95ZHzMxcD31mtntyPGtoA47</div>
        </div>
        
        <div class="password-item" data-id="2">
            <div class="title">공섹썰🌿 비번</div>
            <div class="password">pas6vg3KRhJTai0LARwEfRWYWBiETfBfffHdNnPHI2Ujc0TFp8WIWJMeONxHKCbl1o07jZsiFo6gJLEwX64jzVkW0dijqhsgjnqa</div>
        </div>
        
        <div class="password-item" data-id="3">
            <div class="title">담배 썰 영상 비번</div>
            <div class="password">Fe8tqkSPIj4myPL0wGHcOXt7OnSDlYPYF4PEv1lG778gYaZ3sJ</div>
        </div>
        
        <div class="password-item" data-id="4">
            <div class="title">첫경험 썰 비번</div>
            <div class="password">Dhdjeiei882ue</div>
        </div>
        
        <div class="password-item" data-id="5">
            <div class="title">질싸할 뻔한 썰 비번</div>
            <div class="password">v5W3OZn1vTSpiw1rimJ4aE1sIiQBLBRcVRNntusGpPNkydEPlA73KURVdSNCKplslRco0a8PspdvrvZy1YpZTEwSUIdCTqkaGc4qD9W298kUKeSInVbo4S3mV6UCWp9jKhU7WEO4jKrCeACy1CIlBCJMnI1GPvex7v4qpFtFOvmWLXkSyAWRihs33sLBc47EJ7Xjn2Ne</div>
        </div>
        
        <div class="admin-panel" id="admin-panel" style="display:none;">
            <h3>관리자 패널</h3>
            <div class="toggle-container">
                <label class="toggle-switch">
                    <input type="checkbox" data-id="1" checked>
                    <span class="slider"></span>
                </label>
                <span>공섹썰🌶 비번 활성화</span>
            </div>
            <div class="toggle-container">
                <label class="toggle-switch">
                    <input type="checkbox" data-id="2" checked>
                    <span class="slider"></span>
                </label>
                <span>공섹썰🌿 비번 활성화</span>
            </div>
            <div class="toggle-container">
                <label class="toggle-switch">
                    <input type="checkbox" data-id="3" checked>
                    <span class="slider"></span>
                </label>
                <span>담배 썰 영상 비번 활성화</span>
            </div>
            <div class="toggle-container">
                <label class="toggle-switch">
                    <input type="checkbox" data-id="4" checked>
                    <span class="slider"></span>
                </label>
                <span>첫경험 썰 비번 활성화</span>
            </div>
            <div class="toggle-container">
                <label class="toggle-switch">
                    <input type="checkbox" data-id="5" checked>
                    <span class="slider"></span>
                </label>
                <span>질싸할 뻔한 썰 비번 활성화</span>
            </div>
        </div>
    </div>

    <div class="user-info" id="user-info" style="display:none;">
        <span id="user-email"></span>
        <button class="logout-btn" id="logout-btn">로그아웃</button>
    </div>

    <script src="https://www.gstatic.com/firebasejs/8.10.0/firebase-app.js"></script>
    <script src="https://www.gstatic.com/firebasejs/8.10.0/firebase-auth.js"></script>
    <script>
        // 계정 권한 설정
        const P_READER = ['fjrtufl9909@gmail.com','minjune003956@gmail.com','sexyyousoo68@gmail.com',
                         'seojunna73@gmail.com','chaejun0708@gmail.com','sonhyeonmins@gmail.com',
                         'rang330579@gmail.com','seonuh777@gmail.com','gogumaa0712@gmail.com','kjuho0716@gmail.com'];
        const A_READER = ['shinjonghwan0430@gmail.com','fofmmm1605@gmail.com','shinyousoo68@gmail.com'];
        const B_READER = ['seubuntb@gmail.com'];

        // Firebase 설정
        const firebaseConfig = {
            apiKey: "AIzaSyClivXSor5P8XJHw1rWYsVfxt8iU6_NgBA",
            authDomain: "login-34bef.firebaseapp.com",
            projectId: "login-34bef",
            storageBucket: "login-34bef.appspot.com",
            messagingSenderId: "888738257773",
            appId: "1:888738257773:web:b1c5a99b41996c3ac2d864",
            measurementId: "G-MJB1NJH05M"
        };
        firebase.initializeApp(firebaseConfig);
        const auth = firebase.auth();

        // DOM 요소
        const authContainer = document.getElementById('auth-container');
        const contentContainer = document.getElementById('content-container');
        const userInfo = document.getElementById('user-info');
        const userEmail = document.getElementById('user-email');
        const logoutBtn = document.getElementById('logout-btn');
        const googleLoginBtn = document.getElementById('google-login-btn');
        const adminPanel = document.getElementById('admin-panel');
        const passwordItems = document.querySelectorAll('.password-item');
        const toggleSwitches = document.querySelectorAll('.toggle-switch input');

        // 로그인 상태 확인
        auth.onAuthStateChanged(user => {
            if (user) {
                handleLogin(user);
            } else {
                handleLogout();
            }
        });

        // Google 로그인
        googleLoginBtn.addEventListener('click', () => {
            const provider = new firebase.auth.GoogleAuthProvider();
            auth.signInWithPopup(provider).catch(error => console.error('로그인 오류:', error));
        });

        // 로그아웃
        logoutBtn.addEventListener('click', () => auth.signOut());

        // 로그인 처리
        function handleLogin(user) {
            userEmail.textContent = user.email;
            userInfo.style.display = 'flex';
            authContainer.style.display = 'none';
            contentContainer.classList.add('show');

            // 권한에 따라 UI 조정
            if (P_READER.includes(user.email)) {
                enableAllPasswords();
                adminPanel.style.display = 'none';
            } else if (A_READER.includes(user.email)) {
                enableSelectedPasswords([1, 2, 3]); // 예시로 1,2,3번만 활성화
                adminPanel.style.display = 'none';
            } else if (B_READER.includes(user.email)) {
                enableAllPasswords();
                adminPanel.style.display = 'block';
                initAdminPanel();
            } else {
                enableSelectedPasswords([]); // 권한 없는 사용자
            }
        }

        // 로그아웃 처리
        function handleLogout() {
            userInfo.style.display = 'none';
            authContainer.style.display = 'block';
            contentContainer.classList.remove('show');
        }

        // 모든 비밀번호 활성화
        function enableAllPasswords() {
            passwordItems.forEach(item => {
                item.style.opacity = '1';
                item.style.pointerEvents = 'auto';
            });
        }

        // 선택된 비밀번호만 활성화
        function enableSelectedPasswords(ids) {
            passwordItems.forEach(item => {
                const id = parseInt(item.getAttribute('data-id'));
                if (ids.includes(id)) {
                    item.style.opacity = '1';
                    item.style.pointerEvents = 'auto';
                } else {
                    item.style.opacity = '0.5';
                    item.style.pointerEvents = 'none';
                }
            });
        }

        // 관리자 패널 초기화
        function initAdminPanel() {
            toggleSwitches.forEach(switchEl => {
                const id = parseInt(switchEl.getAttribute('data-id'));
                const item = document.querySelector(`.password-item[data-id="${id}"]`);
                
                switchEl.addEventListener('change', () => {
                    if (switchEl.checked) {
                        item.style.opacity = '1';
                        item.style.pointerEvents = 'auto';
                    } else {
                        item.style.opacity = '0.5';
                        item.style.pointerEvents = 'none';
                    }
                });
            });
        }

        // 비밀번호 복사 기능
        passwordItems.forEach(item => {
            item.addEventListener('click', () => {
                const password = item.querySelector('.password').textContent;
                navigator.clipboard.writeText(password).then(() => {
                    alert('비밀번호가 복사되었습니다!');
                }).catch(err => {
                    console.error('복사 실패:', err);
                });
            });
        });

        // 사이트 경유 경로 체크
        if (document.referrer !== "https://yousoo68.github.io/ssul/") {
            window.location.href = "https://yousoo68.github.io/ssul/";
        }
    </script>
</body>
</html>

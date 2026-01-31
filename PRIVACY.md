<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    body { font-family: sans-serif; max-width: 800px; margin: 0 auto; padding: 20px; line-height: 1.6; }
    h1 { color: #333; border-bottom: 2px solid #eee; padding-bottom: 10px; }
    h2 { color: #555; margin-top: 30px; }
    .btn-group { margin-bottom: 30px; text-align: center; }
    .btn { 
        display: inline-block; padding: 10px 15px; margin: 5px; 
        border: 1px solid #ddd; border-radius: 5px; cursor: pointer; 
        background-color: #f9f9f9; font-weight: bold; text-decoration: none; color: #333;
    }
    .btn:hover { background-color: #eee; }
    .btn.active { background-color: #333; color: white; border-color: #333; }
    .content-section { display: none; } /* 기본적으로 다 숨김 */
    .show { display: block; } /* 선택된 것만 보임 */
</style>
<script>
    function showLang(langId) {
        // 모든 내용을 숨김
        var contents = document.getElementsByClassName('content-section');
        for (var i = 0; i < contents.length; i++) {
            contents[i].style.display = 'none';
        }
        // 모든 버튼의 활성화 표시를 끔
        var buttons = document.getElementsByClassName('btn');
        for (var i = 0; i < buttons.length; i++) {
            buttons[i].classList.remove('active');
        }
        // 선택한 언어만 보여줌
        document.getElementById(langId).style.display = 'block';
        // 선택한 버튼을 활성화함
        document.getElementById('btn-' + langId).classList.add('active');
    }
</script>
</head>
<body>

<div class="btn-group">
    <a id="btn-en" class="btn active" onclick="showLang('en')">English</a>
    <a id="btn-ko" class="btn" onclick="showLang('ko')">한국어</a>
    <a id="btn-ja" class="btn" onclick="showLang('ja')">日本語</a>
    <a id="btn-zh" class="btn" onclick="showLang('zh')">中文</a>
    <a id="btn-es" class="btn" onclick="showLang('es')">Español</a>
</div>

<div id="en" class="content-section" style="display: block;">
    <h1>Privacy Policy</h1>
    <p><strong>Effective Date:</strong> 2026-01-31</p>
    <p><strong>Vignette Studio</strong> ("we", "our", or "us") operates the mobile game application <strong>Block Bomb</strong> (the "Service"). We are committed to protecting your privacy.</p>
    
    <h3>1. Information Collection and Use</h3>
    <p>We do not require you to create an account. We do not store your personal data on our servers. However, the Service may use third-party services that collect Device Information, Advertising ID, and IP address.</p>

    <h3>2. Third-Party Services</h3>
    <ul>
        <li><strong>Google AdMob / Firebase:</strong> <a href="https://policies.google.com/privacy">Google Privacy Policy</a></li>
        <li><strong>Unity Ads / Analytics:</strong> <a href="https://unity3d.com/legal/privacy-policy">Unity Privacy Policy</a></li>
    </ul>

    <h3>3. Contact Us</h3>
    <p>
        <strong>Studio Name:</strong> Vignette Studio<br>
        <strong>Email:</strong> vignettemanager@gmail.com
    </p>
</div>

<div id="ko" class="content-section">
    <h1>개인정보 처리방침</h1>
    <p><strong>시행일:</strong> 2026년 1월 31일</p>
    <p><strong>Vignette Studio</strong>는 <strong>Block Bomb</strong> (이하 "서비스") 이용과 관련하여 사용자의 개인정보를 소중하게 생각합니다.</p>

    <h3>1. 수집하는 개인정보 항목</h3>
    <p>회원가입이 필요 없으며, 개발사가 직접 개인정보를 서버에 저장하지 않습니다. 단, 광고 송출을 위해 기기 정보 및 광고 식별자가 제3자 서비스에 의해 수집될 수 있습니다.</p>

    <h3>2. 제3자 서비스 제공자</h3>
    <ul>
        <li><strong>Google AdMob / Firebase:</strong> <a href="https://policies.google.com/privacy">Google 개인정보 처리방침</a></li>
        <li><strong>Unity Ads / Analytics:</strong> <a href="https://unity3d.com/legal/privacy-policy">Unity 개인정보 처리방침</a></li>
    </ul>

    <h3>3. 문의하기</h3>
    <p>
        <strong>스튜디오명:</strong> Vignette Studio<br>
        <strong>이메일:</strong> vignettemanager@gmail.com
    </p>
</div>

<div id="ja" class="content-section">
    <h1>プライバシーポリシー</h1>
    <p><strong>発効日:</strong> 2026年1月31日</p>
    <p><strong>Vignette Studio</strong>（以下「当社」）は、<strong>Block Bomb</strong>（以下「本サービス」）における利用者の個人情報の取扱いについて以下の通り定めます。</p>

    <h3>1. 収集する情報</h3>
    <p>会員登録は不要であり、当社が個人情報をサーバーに保存することはありません。ただし、広告配信のために第三者サービスが端末情報や広告IDを収集する場合があります。</p>

    <h3>2. 第三者サービス</h3>
    <ul>
        <li><strong>Google AdMob / Firebase:</strong> <a href="https://policies.google.com/privacy">Google プライバシーポリシー</a></li>
        <li><strong>Unity Ads / Analytics:</strong> <a href="https://unity3d.com/legal/privacy-policy">Unity プライバシーポリシー</a></li>
    </ul>

    <h3>3. お問い合わせ</h3>
    <p>
        <strong>スタジオ名:</strong> Vignette Studio<br>
        <strong>メール:</strong> vignettemanager@gmail.com
    </p>
</div>

<div id="zh" class="content-section">
    <h1>隐私政策</h1>
    <p><strong>生效日期:</strong> 2026年1月31日</p>
    <p><strong>Vignette Studio</strong>（以下简称“我们”）非常重视用户的隐私。本隐私政策适用于 <strong>Block Bomb</strong>。</p>

    <h3>1. 信息收集与使用</h3>
    <p>使用本服务无需注册账号，我们也不会在服务器上存储您的个人信息。为了提供广告，第三方服务可能会收集您的设备信息和广告ID。</p>

    <h3>2. 第三方服务</h3>
    <ul>
        <li><strong>Google AdMob / Firebase:</strong> <a href="https://policies.google.com/privacy">Google 隐私权政策</a></li>
        <li><strong>Unity Ads / Analytics:</strong> <a href="https://unity3d.com/legal/privacy-policy">Unity 隐私政策</a></li>
    </ul>

    <h3>3. 联系我们</h3>
    <p>
        <strong>工作室名称:</strong> Vignette Studio<br>
        <strong>电子邮件:</strong> vignettemanager@gmail.com
    </p>
</div>

<div id="es" class="content-section">
    <h1>Política de privacidad</h1>
    <p><strong>Fecha de vigencia:</strong> 31 de enero de 2026</p>
    <p><strong>Vignette Studio</strong> se compromete a proteger su privacidad en relación con el uso de <strong>Block Bomb</strong>.</p>

    <h3>1. Recopilación y uso de información</h3>
    <p>No requerimos la creación de una cuenta ni almacenamos datos personales en nuestros servidores. Sin embargo, los servicios de terceros pueden recopilar información del dispositivo e ID de publicidad.</p>

    <h3>2. Servicios de terceros</h3>
    <ul>
        <li><strong>Google AdMob / Firebase:</strong> <a href="https://policies.google.com/privacy">Política de privacidad de Google</a></li>
        <li><strong>Unity Ads / Analytics:</strong> <a href="https://unity3d.com/legal/privacy-policy">Política de privacidad de Unity</a></li>
    </ul>

    <h3>3. Contáctenos</h3>
    <p>
        <strong>Nombre del estudio:</strong> Vignette Studio<br>
        <strong>Correo electrónico:</strong> vignettemanager@gmail.com
    </p>
</div>

</body>
</html>

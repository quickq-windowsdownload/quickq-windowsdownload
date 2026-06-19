<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>QuickQ【官方网站】-全球网络加速·低延迟畅玩</title>
    <meta name="description" content="QuickQ官方从2012年开始为用户提供专业跨境网络加速服务，采用自研加密算法，高效的传输线路，为各种需求客户提供游戏加速、海外流媒体解锁、外贸办公专线，全球200+节点极速稳定，免费试用。">
    <meta name="keywords" content="QuickQ,网络加速,游戏加速器,低延迟,海外加速,免费加速,专线加速,QuickQ官网">
    <meta name="robots" content="index, follow">
    <meta name="applicable-device" content="pc,mobile">
    <link rel="canonical" href="http://hvscloud.com">
    <!-- Open Graph -->
    <meta property="og:title" content="QuickQ【官方网站】-全球网络加速·低延迟畅玩">
    <meta property="og:description" content="QuickQ官方从2012年开始为用户提供专业跨境网络加速服务，采用自研加密算法，高效的传输线路，为各种需求客户提供游戏加速、海外流媒体解锁、外贸办公专线，全球200+节点极速稳定，免费试用。">
    <meta property="og:image" content="https://via.placeholder.com/1200x630/3b82f6/ffffff?text=QuickQ">
    <meta property="og:type" content="website">
    <!-- 结构化数据 -->
    <script type="application/ld+json">
        {
            "@context": "https://schema.org",
            "@type": "SoftwareApplication",
            "name": "QuickQ",
            "applicationCategory": "UtilityApplication",
            "operatingSystem": "Windows, macOS, Android, iOS",
            "description": "专业跨境网络加速工具，游戏/流媒体/办公多场景加速",
            "offers": {
                "@type": "AggregateOffer",
                "priceCurrency": "CNY",
                "lowPrice": "19",
                "highPrice": "299",
                "offerCount": "4"
            }
        }
    </script>
    <style>
        :root {
            --sky-blue: #3b82f6;
            --sky-light: #60a5fa;
            --sky-pale: #dbeafe;
            --accent-coral: #f97316;
            --bg-page: #f8fafc;
            --bg-white: #ffffff;
            --text-main: #1e293b;
            --text-secondary: #475569;
            --text-muted: #94a3b8;
            --border-light: #e2e8f0;
            --border-medium: #cbd5e1;
            --shadow-sm: 0 1px 3px rgba(0,0,0,0.06);
            --shadow-card: 0 8px 24px rgba(0,0,0,0.05);
            --shadow-hover: 0 12px 32px rgba(0,0,0,0.08);
            --radius-md: 12px;
            --radius-lg: 20px;
            --radius-xl: 28px;
            --font-display: 'PingFang SC', 'Microsoft YaHei', 'Inter', sans-serif;
            --font-body: 'PingFang SC', 'Microsoft YaHei', 'Segoe UI', system-ui;
            --transition-base: all 0.25s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        html {
            scroll-behavior: smooth;
            font-size: 16px;
        }
        body {
            font-family: var(--font-body);
            background-color: var(--bg-page);
            color: var(--text-main);
            line-height: 1.6;
            -webkit-font-smoothing: antialiased;
        }

        /* 导航栏 - 浅色透明 */
        .nav-container {
            position: sticky;
            top: 0;
            z-index: 1000;
            background: rgba(255,255,255,0.88);
            backdrop-filter: blur(14px);
            -webkit-backdrop-filter: blur(14px);
            border-bottom: 1px solid var(--border-light);
            transition: var(--transition-base);
        }
        .nav-inner {
            max-width: 1240px;
            margin: 0 auto;
            padding: 0 24px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            height: 68px;
        }
        .logo-group {
            display: flex;
            align-items: center;
            gap: 10px;
            text-decoration: none;
            color: var(--text-main);
            flex-shrink: 0;
        }
        .logo-icon {
            width: 40px;
            height: 40px;
            background: linear-gradient(135deg, #3b82f6, #2563eb);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            font-weight: 700;
            font-size: 20px;
            box-shadow: 0 4px 10px rgba(59,130,246,0.3);
        }
        .logo-text {
            font-weight: 700;
            font-size: 1.3rem;
            font-family: var(--font-display);
            letter-spacing: 0.5px;
        }
        .nav-links {
            display: flex;
            list-style: none;
            gap: 4px;
            align-items: center;
        }
        .nav-links a {
            text-decoration: none;
            color: var(--text-secondary);
            font-weight: 500;
            padding: 8px 18px;
            border-radius: 24px;
            font-size: 0.95rem;
            transition: var(--transition-base);
            white-space: nowrap;
        }
        .nav-links a:hover, .nav-links a.link-active {
            color: #1e293b;
            background: #f1f5f9;
        }
        .btn-nav-download {
            background: #3b82f6 !important;
            color: #fff !important;
            font-weight: 600 !important;
            padding: 9px 22px !important;
            border-radius: 24px !important;
            box-shadow: 0 2px 12px rgba(59,130,246,0.35);
        }
        .btn-nav-download:hover {
            background: #2563eb !important;
            transform: translateY(-1px);
        }
        .menu-toggle {
            display: none;
            background: none;
            border: none;
            flex-direction: column;
            gap: 5px;
            padding: 6px;
            cursor: pointer;
        }
        .menu-toggle span {
            width: 26px;
            height: 2px;
            background: #1e293b;
            border-radius: 3px;
        }

        /* 英雄区 */
        .hero-wrapper {
            background: linear-gradient(135deg, #f0f9ff 0%, #ffffff 60%, #e0f2fe 100%);
            padding: 60px 24px 70px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        .hero-wrapper::before {
            content: '';
            position: absolute;
            top: -100px;
            right: -80px;
            width: 350px;
            height: 350px;
            background: radial-gradient(circle, rgba(59,130,246,0.15) 0%, transparent 70%);
            border-radius: 50%;
            z-index: 0;
        }
        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            margin: 0 auto;
        }
        .hero-tag {
            display: inline-block;
            background: #fff;
            border: 1px solid var(--border-light);
            padding: 6px 18px;
            border-radius: 24px;
            font-size: 0.8rem;
            font-weight: 600;
            color: #3b82f6;
            letter-spacing: 1px;
            margin-bottom: 18px;
            box-shadow: var(--shadow-sm);
        }
        .hero-title {
            font-family: var(--font-display);
            font-size: 2.6rem;
            font-weight: 800;
            line-height: 1.3;
            color: #0f172a;
            margin-bottom: 14px;
        }
        .hero-title span {
            background: linear-gradient(to right, #2563eb, #7c3aed);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .hero-desc {
            font-size: 1.05rem;
            color: #475569;
            max-width: 550px;
            margin: 0 auto 28px;
        }
        .hero-buttons {
            display: flex;
            gap: 14px;
            justify-content: center;
            flex-wrap: wrap;
        }
        .btn-solid-blue {
            background: #3b82f6;
            color: #fff;
            padding: 14px 32px;
            border-radius: 30px;
            font-weight: 700;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            transition: var(--transition-base);
            box-shadow: 0 6px 18px rgba(59,130,246,0.35);
            border: none;
            cursor: pointer;
            font-size: 1rem;
        }
        .btn-solid-blue:hover {
            background: #2563eb;
            transform: translateY(-2px);
            box-shadow: 0 8px 24px rgba(59,130,246,0.45);
        }
        .btn-outline-dark {
            background: transparent;
            border: 2px solid #cbd5e1;
            color: #1e293b;
            padding: 14px 32px;
            border-radius: 30px;
            font-weight: 600;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            transition: var(--transition-base);
            font-size: 1rem;
        }
        .btn-outline-dark:hover {
            border-color: #3b82f6;
            background: #f8fafc;
            color: #2563eb;
        }
        .hero-stats {
            display: flex;
            justify-content: center;
            gap: 48px;
            margin-top: 40px;
            flex-wrap: wrap;
        }
        .stat-block strong {
            display: block;
            font-size: 2rem;
            font-weight: 800;
            color: #0f172a;
            font-family: var(--font-display);
        }
        .stat-block span {
            font-size: 0.85rem;
            color: #64748b;
        }

        /* 通用区块 */
        .section-wrap {
            max-width: 1200px;
            margin: 0 auto;
            padding: 64px 24px;
        }
        .section-header {
            text-align: center;
            margin-bottom: 48px;
        }
        .section-label {
            display: inline-block;
            font-size: 0.8rem;
            font-weight: 700;
            letter-spacing: 2px;
            color: #3b82f6;
            background: #eff6ff;
            padding: 4px 14px;
            border-radius: 20px;
            margin-bottom: 10px;
        }
        .section-title {
            font-family: var(--font-display);
            font-size: 2rem;
            font-weight: 700;
            margin-bottom: 10px;
            color: #0f172a;
        }
        .section-sub {
            color: #64748b;
            max-width: 540px;
            margin: 0 auto;
        }

        /* 核心功能 */
        .feature-cards-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 24px;
        }
        .feat-card {
            background: #fff;
            border-radius: var(--radius-lg);
            padding: 28px 22px;
            border: 1px solid var(--border-light);
            text-align: center;
            transition: var(--transition-base);
            box-shadow: var(--shadow-sm);
        }
        .feat-card:hover {
            transform: translateY(-6px);
            box-shadow: var(--shadow-hover);
            border-color: #bfdbfe;
        }
        .feat-icon {
            width: 56px;
            height: 56px;
            background: #eff6ff;
            border-radius: 16px;
            margin: 0 auto 16px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 26px;
        }
        .feat-card h3 {
            font-family: var(--font-display);
            font-size: 1.1rem;
            font-weight: 700;
            margin-bottom: 6px;
        }
        .feat-card p {
            color: #64748b;
            font-size: 0.9rem;
            line-height: 1.6;
        }
        .feat-card img {
            width: 100%;
            height: 120px;
            object-fit: cover;
            border-radius: 12px;
            margin-top: 14px;
            opacity: 0.9;
            transition: var(--transition-base);
        }
        .feat-card:hover img {
            opacity: 1;
        }

        /* 软件展示 */
        #display-software {
            background: #fff;
        }
        .display-row {
            display: flex;
            gap: 48px;
            align-items: center;
            flex-wrap: wrap;
        }
        .display-img {
            flex: 1;
            min-width: 280px;
        }
        .display-img img {
            width: 100%;
            border-radius: var(--radius-xl);
            box-shadow: var(--shadow-card);
        }
        .display-text {
            flex: 1;
            min-width: 280px;
        }
        .display-text h3 {
            font-size: 1.7rem;
            font-weight: 700;
            margin-bottom: 12px;
        }
        .display-text p {
            color: #475569;
            margin-bottom: 14px;
        }
        .checklist {
            list-style: none;
        }
        .checklist li {
            padding: 6px 0 6px 26px;
            position: relative;
            color: #334155;
        }
        .checklist li::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: #10b981;
            font-weight: bold;
        }
        .platform-tags {
            display: flex;
            gap: 10px;
            margin-top: 16px;
            flex-wrap: wrap;
        }
        .plat-tag {
            background: #f1f5f9;
            padding: 6px 16px;
            border-radius: 20px;
            font-size: 0.85rem;
            color: #1e293b;
            display: flex;
            align-items: center;
            gap: 5px;
            border: 1px solid #e2e8f0;
        }

        /* 套餐选择 */
        .pricing-grid-4 {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
        }
        .plan-item {
            background: #fff;
            border-radius: var(--radius-xl);
            padding: 28px 18px;
            text-align: center;
            border: 2px solid #e2e8f0;
            transition: var(--transition-base);
            position: relative;
        }
        .plan-item.popular-plan {
            border-color: #3b82f6;
            box-shadow: 0 0 0 3px rgba(59,130,246,0.15), var(--shadow-card);
            transform: scale(1.02);
            z-index: 2;
        }
        .plan-item:hover {
            border-color: #94a3b8;
            transform: translateY(-4px);
            box-shadow: var(--shadow-hover);
        }
        .popular-plan:hover {
            transform: scale(1.02) translateY(-4px);
        }
        .popular-badge {
            position: absolute;
            top: -14px;
            left: 50%;
            transform: translateX(-50%);
            background: #f97316;
            color: #fff;
            padding: 4px 16px;
            border-radius: 14px;
            font-size: 0.75rem;
            font-weight: 700;
            letter-spacing: 0.5px;
            white-space: nowrap;
        }
        .plan-name {
            font-weight: 700;
            font-size: 1.2rem;
            margin-bottom: 8px;
        }
        .plan-price {
            font-size: 2.3rem;
            font-weight: 800;
            color: #0f172a;
            font-family: var(--font-display);
        }
        .plan-price sub {
            font-size: 1rem;
            color: #94a3b8;
            font-weight: 500;
        }
        .plan-duration {
            color: #64748b;
            font-size: 0.85rem;
            margin-bottom: 16px;
        }
        .plan-features {
            list-style: none;
            text-align: left;
            margin-bottom: 20px;
        }
        .plan-features li {
            padding: 5px 0 5px 22px;
            font-size: 0.85rem;
            color: #475569;
            position: relative;
        }
        .plan-features li::before {
            content: '●';
            position: absolute;
            left: 0;
            color: #3b82f6;
            font-size: 0.6rem;
            top: 9px;
        }
        .btn-plan {
            display: block;
            width: 100%;
            padding: 11px;
            border-radius: 24px;
            font-weight: 700;
            background: #f1f5f9;
            border: 1px solid #e2e8f0;
            color: #1e293b;
            cursor: pointer;
            transition: var(--transition-base);
            font-size: 0.9rem;
        }
        .btn-plan:hover {
            background: #3b82f6;
            color: #fff;
            border-color: #3b82f6;
            box-shadow: 0 4px 12px rgba(59,130,246,0.3);
        }
        .popular-plan .btn-plan {
            background: #3b82f6;
            color: #fff;
            border-color: #3b82f6;
        }
        .popular-plan .btn-plan:hover {
            background: #2563eb;
        }

        /* 常见问题 */
        .faq-container {
            max-width: 760px;
            margin: 0 auto;
        }
        .faq-card {
            background: #fff;
            border: 1px solid var(--border-light);
            border-radius: var(--radius-md);
            margin-bottom: 10px;
            overflow: hidden;
            transition: var(--transition-base);
        }
        .faq-card:hover {
            border-color: #bfdbfe;
        }
        .faq-question {
            width: 100%;
            padding: 18px 20px;
            background: none;
            border: none;
            font-weight: 600;
            font-size: 1rem;
            text-align: left;
            display: flex;
            justify-content: space-between;
            align-items: center;
            cursor: pointer;
            color: #1e293b;
            font-family: var(--font-display);
            transition: background 0.2s;
        }
        .faq-question:hover {
            background: #f8fafc;
        }
        .faq-arrow {
            font-size: 1.2rem;
            color: #94a3b8;
            transition: transform 0.3s;
        }
        .faq-card.open .faq-arrow {
            transform: rotate(180deg);
            color: #3b82f6;
        }
        .faq-answer {
            max-height: 0;
            overflow: hidden;
            padding: 0 20px;
            background: #f9fafb;
            color: #475569;
            font-size: 0.9rem;
            line-height: 1.7;
            transition: max-height 0.35s ease, padding 0.35s ease;
        }
        .faq-card.open .faq-answer {
            max-height: 200px;
            padding: 16px 20px;
        }

        /* CTA区域 */
        .cta-block {
            text-align: center;
            background: #fff;
            border-radius: var(--radius-xl);
            padding: 44px 24px;
            border: 1px solid var(--border-light);
            box-shadow: var(--shadow-sm);
        }

        /* 底部 */
        .footer-corporate {
            background: #0f172a;
            color: #cbd5e1;
            padding: 48px 24px 20px;
            font-size: 0.85rem;
        }
        .footer-grid {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 2fr 1fr 1fr 1.3fr;
            gap: 32px;
            padding-bottom: 28px;
            border-bottom: 1px solid #1e293b;
        }
        .footer-col h4 {
            color: #f1f5f9;
            font-weight: 700;
            margin-bottom: 14px;
            font-size: 1rem;
        }
        .footer-col ul {
            list-style: none;
        }
        .footer-col li {
            margin-bottom: 8px;
        }
        .footer-col a {
            color: #94a3b8;
            text-decoration: none;
        }
        .footer-col a:hover {
            color: #60a5fa;
        }
        .footer-bottom {
            max-width: 1200px;
            margin: 0 auto;
            padding-top: 16px;
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 10px;
            color: #64748b;
        }
        .footer-bottom a {
            color: #94a3b8;
            text-decoration: none;
            margin-left: 14px;
        }
        .footer-bottom a:hover {
            color: #60a5fa;
        }

        /* 响应式 */
        @media (max-width: 1024px) {
            .feature-cards-grid { grid-template-columns: repeat(2,1fr); }
            .pricing-grid-4 { grid-template-columns: repeat(2,1fr); }
            .popular-plan { transform: scale(1); }
            .popular-plan:hover { transform: translateY(-4px); }
            .footer-grid { grid-template-columns: 1fr 1fr; }
        }
        @media (max-width: 768px) {
            .nav-links {
                display: none;
                position: absolute;
                top: 68px;
                left: 0;
                right: 0;
                background: #fff;
                flex-direction: column;
                padding: 16px;
                border-bottom: 1px solid #e2e8f0;
                box-shadow: 0 10px 20px rgba(0,0,0,0.05);
            }
            .nav-links.mobile-open { display: flex; }
            .menu-toggle { display: flex; }
            .hero-title { font-size: 2rem; }
            .feature-cards-grid { grid-template-columns: 1fr; }
            .pricing-grid-4 { grid-template-columns: 1fr 1fr; }
            .display-row { flex-direction: column; }
            .footer-grid { grid-template-columns: 1fr; }
        }
        @media (max-width: 480px) {
            .pricing-grid-4 { grid-template-columns: 1fr; }
            .hero-buttons { flex-direction: column; align-items: center; }
            .section-title { font-size: 1.6rem; }
        }
    </style>
</head>
<body>
    <!-- 导航 -->
    <header class="nav-container" id="topNav">
        <div class="nav-inner">
            <a href="/" class="logo-group" title="QuickQ官网">
                <div class="logo-icon">无</div>
                <span class="logo-text">QuickQ</span>
            </a>
            <button class="menu-toggle" id="menuToggle" aria-label="菜单">
                <span></span><span></span><span></span>
            </button>
            <nav>
                <ul class="nav-links" id="navMenu">
                    <li><a href="#core-capabilities" class="link-active">核心功能</a></li>
                    <li><a href="#display-software">软件展示</a></li>
                    <li><a href="#plan-list">套餐选择</a></li>
                    <li><a href="#faq-block">常见问题</a></li>
                    <li><a href="#download-area" class="btn-nav-download">立即下载</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- 英雄区 -->
    <section class="hero-wrapper">
        <div class="hero-content">
            <div class="hero-tag">🌐 全球加速 · 畅享无忧</div>
            <h1 class="hero-title">用<span>QuickQ</span><br>打开世界网络之门</h1>
            <p class="hero-desc">无论是游戏对战、高清追剧还是跨境办公，QuickQ为您提供<strong>稳定低延迟</strong>的专线加速服务，覆盖200+国家和地区。</p>
            <div class="hero-buttons">
                <a href="#download-area" class="btn-solid-blue">
                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M12 16l-6-6h4V4h4v6h4l-6 6z" fill="currentColor"/><path d="M4 20h16v-2H4v2z" fill="currentColor"/></svg>
                    免费下载客户端
                </a>
                <a href="#plan-list" class="btn-outline-dark">
                    📋 查看套餐详情
                </a>
            </div>
            <div class="hero-stats">
                <div class="stat-block"><strong>99.9%</strong><span>可用率保障</span></div>
                <div class="stat-block"><strong>200+</strong><span>全球节点</span></div>
                <div class="stat-block"><strong>3000万+</strong><span>用户选择</span></div>
            </div>
        </div>
    </section>

    <!-- 核心功能 -->
    <section id="core-capabilities" class="section-wrap">
        <div class="section-header">
            <span class="section-label">核心能力</span>
            <h2 class="section-title">六大加速科技，体验全面升级</h2>
            <p class="section-sub">QuickQ自研加速引擎，从网络底层解决延迟与卡顿。</p>
        </div>
        <div class="feature-cards-grid">
            <div class="feat-card">
                <div class="feat-icon">⚡</div>
                <h3>智能路径优选</h3>
                <p>动态监测全球节点负载，实时切换最优传输路径，绕过网络拥堵。</p>
                
            </div>
            <div class="feat-card">
                <div class="feat-icon">🔒</div>
                <h3>金融级加密</h3>
                <p>采用AES-256加密协议，保护数据传输安全，防止隐私泄露。</p>
               
            </div>
            <div class="feat-card">
                <div class="feat-icon">🌍</div>
                <h3>全球区服覆盖</h3>
                <p>亚洲、欧美、中东等节点深度覆盖，满足各类游戏及流媒体需求。</p>
                
            </div>
            <div class="feat-card">
                <div class="feat-icon">🎮</div>
                <h3>游戏模式定制</h3>
                <p>自动识别热门游戏，启用专属加速策略，FPS/MOBA专项优化。</p>
               
            </div>
            <div class="feat-card">
                <div class="feat-icon">📱</div>
                <h3>全端无缝切换</h3>
                <p>支持Windows/macOS/Android/iOS/路由器，账号通用，一键同步。</p>
                
            </div>
            <div class="feat-card">
                <div class="feat-icon">🛠️</div>
                <h3>网络诊断修复</h3>
                <p>内置专业诊断工具，自动检测网络环境并推荐最佳设置方案。</p>
                
            </div>
        </div>
    </section>

    <!-- 软件展示 -->
    <section id="display-software" class="section-wrap">
        <div class="section-header">
            <span class="section-label">客户端预览</span>
            <h2 class="section-title">简洁高效，上手零门槛</h2>
            <p class="section-sub">优雅的界面设计，让网络加速变得前所未有的简单。</p>
        </div>
        <div class="display-row">
            <div class="display-img">
               
            </div>
            <div class="display-text">
                <h3>一键加速，畅快体验</h3>
                <p>下载安装后，选择目标游戏或应用，点击中央加速按钮即可。无需复杂设置，系统自动匹配最优节点，实时显示网络状态。</p>
                <ul class="checklist">
                    <li>延迟与丢包率实时可视化</li>
                    <li>内置测速工具，节点秒级切换</li>
                    <li>支持自定义加速规则与黑白名单</li>
                    <li>轻量级后台运行，资源占用极低</li>
                </ul>
                <div class="platform-tags">
                    <span class="plat-tag">🖥️ Windows</span>
                    <span class="plat-tag">🍎 macOS</span>
                    <span class="plat-tag">📱 Android</span>
                    <span class="plat-tag">📱 iOS</span>
                    <span class="plat-tag">📡 OpenWrt</span>
                </div>
            </div>
        </div>
    </section>

    <!-- 套餐选择 -->
    <section id="plan-list" class="section-wrap">
        <div class="section-header">
            <span class="section-label">灵活套餐</span>
            <h2 class="section-title">选择适合您的加速方案</h2>
            <p class="section-sub">新用户免费试用3天，所有套餐支持7天无忧退款。</p>
        </div>
        <div class="pricing-grid-4">
            <div class="plan-item">
                <div class="plan-name">入门体验</div>
                <div class="plan-price">¥19<sub>/月</sub></div>
                <div class="plan-duration">按月订阅 · 灵活取消</div>
                <ul class="plan-features">
                    <li>2台设备同时在线</li>
                    <li>50GB月度流量</li>
                    <li>标准节点加速</li>
                    <li>基础客服支持</li>
                </ul>
                <button class="btn-plan" onclick="alert('即将跳转支付：入门体验套餐')">立即订阅</button>
            </div>
            <div class="plan-item popular-plan">
                <span class="popular-badge">🔥 最受欢迎</span>
                <div class="plan-name">季度畅玩</div>
                <div class="plan-price">¥49<sub>/季</sub></div>
                <div class="plan-duration">月均¥16.3 · 省35%</div>
                <ul class="plan-features">
                    <li>5台设备同时在线</li>
                    <li>200GB月度流量</li>
                    <li>全节点高速加速</li>
                    <li>游戏专线优先</li>
                    <li>VIP客服通道</li>
                </ul>
                <button class="btn-plan" onclick="alert('即将跳转支付：季度畅玩套餐')">立即订阅</button>
            </div>
            <div class="plan-item">
                <div class="plan-name">年度巨划算</div>
                <div class="plan-price">¥149<sub>/年</sub></div>
                <div class="plan-duration">月均¥12.4 · 省55%</div>
                <ul class="plan-features">
                    <li>10台设备同时在线</li>
                    <li>无限流量畅用</li>
                    <li>全节点+游戏专线</li>
                    <li>流媒体解锁支持</li>
                    <li>VIP专属客服</li>
                </ul>
                <button class="btn-plan" onclick="alert('即将跳转支付：年度巨划算套餐')">立即订阅</button>
            </div>
            <div class="plan-item">
                <div class="plan-name">永久尊享</div>
                <div class="plan-price">¥299<sub>/永久</sub></div>
                <div class="plan-duration">一次付费 · 终身使用</div>
                <ul class="plan-features">
                    <li>15台设备同时在线</li>
                    <li>无限流量 · 永久有效</li>
                    <li>全功能无限制</li>
                    <li>SVIP专属服务</li>
                    <li>未来功能免费升级</li>
                </ul>
                <button class="btn-plan" onclick="alert('即将跳转支付：永久尊享套餐')">立即订阅</button>
            </div>
        </div>
    </section>

    <!-- 常见问题 -->
    <section id="faq-block" class="section-wrap">
        <div class="section-header">
            <span class="section-label">常见疑问</span>
            <h2 class="section-title">您关心的问题都在这里</h2>
        </div>
        <div class="faq-container">
            <div class="faq-card open">
                <button class="faq-question">QuickQ支持哪些游戏？<span class="faq-arrow">▼</span></button>
                <div class="faq-answer"><p>支持LOL、CS2、Dota2、Valorant、原神国际服等1000+款热门游戏，以及Steam、Epic、战网等平台。流媒体方面支持Netflix、YouTube等。</p></div>
            </div>
            <div class="faq-card">
                <button class="faq-question">免费试用有什么限制吗？<span class="faq-arrow">▼</span></button>
                <div class="faq-answer"><p>新用户注册即享3天全功能免费试用，体验所有节点与功能，无需绑定支付方式。</p></div>
            </div>
            <div class="faq-card">
                <button class="faq-question">一个账号能在多台电脑上使用吗？<span class="faq-arrow">▼</span></button>
                <div class="faq-answer"><p>可以，不同套餐允许不同数量的设备同时在线。入门版2台，季度版5台，年度版10台，永久版15台。</p></div>
            </div>
            <div class="faq-card">
                <button class="faq-question">使用后网络延迟没有改善怎么办？<span class="faq-arrow">▼</span></button>
                <div class="faq-answer"><p>我们提供7天无理由退款保障。如果加速效果不理想，可联系客服申请全额退款。</p></div>
            </div>
            <div class="faq-card">
                <button class="faq-question">需要安装额外驱动吗？<span class="faq-arrow">▼</span></button>
                <div class="faq-answer"><p>无需额外驱动，下载安装客户端后登录即可使用，软件体积小，对系统无负担。</p></div>
            </div>
        </div>
    </section>

    <!-- 下载号召 -->
    <section id="download-area" class="section-wrap">
        <div class="cta-block">
            <h2 style="font-size:1.8rem; font-weight:700; margin-bottom:8px;">准备好畅游全球网络了吗？</h2>
            <p style="color:#475569; margin-bottom:20px;">点击下载QuickQ，即刻开启极速之旅。</p>
            <a href="#" class="btn-solid-blue" style="font-size:1.1rem; padding:16px 38px;">
                <svg width="22" height="22" viewBox="0 0 24 24" fill="none"><path d="M12 16l-6-6h4V4h4v6h4l-6 6z" fill="currentColor"/><path d="M4 20h16v-2H4v2z" fill="currentColor"/></svg>
                免费下载 Windows 客户端
            </a>
            <p style="color:#94a3b8; font-size:0.8rem; margin-top:10px;">兼容 macOS / Android / iOS · 最新版本 v5.3.0</p>
        </div>
    </section>

    <!-- 底部 - 企业官网形式 -->
    <footer class="footer-corporate">
        <div class="footer-grid">
            <div class="footer-col">
                <div style="display:flex;align-items:center;gap:8px;margin-bottom:12px;">
                    <div style="width:34px;height:34px;background:#2563eb;border-radius:10px;display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;">无</div>
                    <span style="font-weight:700;color:#f1f5f9;font-size:1.1rem;">QuickQ</span>
                </div>
                <p style="line-height:1.7;">深圳无忧网络科技有限公司是一家专注网络加速技术研发的创新型科技企业，致力于为全球用户提供稳定、安全、高效的网络连接服务。</p>
                <div style="margin-top:10px;display:flex;gap:8px;flex-wrap:wrap;">
                    <span style="background:#1e293b;padding:4px 10px;border-radius:12px;font-size:0.7rem;">ISO 27001</span>
                    <span style="background:#1e293b;padding:4px 10px;border-radius:12px;font-size:0.7rem;">增值电信许可</span>
                </div>
            </div>
            <div class="footer-col">
                <h4>产品</h4>
                <ul>
                    <li><a href="#">Windows版</a></li>
                    <li><a href="#">macOS版</a></li>
                    <li><a href="#">移动端</a></li>
                    <li><a href="#">路由器插件</a></li>
                </ul>
            </div>
            <div class="footer-col">
                <h4>支持</h4>
                <ul>
                    <li><a href="#">帮助中心</a></li>
                    <li><a href="#">使用教程</a></li>
                    <li><a href="#">联系客服</a></li>
                    <li><a href="#">意见反馈</a></li>
                </ul>
            </div>
            <div class="footer-col">
                <h4>联系方式</h4>
                <ul>
                    <li>📧 support@wuyou加速器.com</li>
                    <li>📞 400-800-无忧</li>
                    <li>📍 深圳市南山区无忧科技园</li>
                    <li>🕐 周一至周日 9:00 - 22:00</li>
                </ul>
            </div>
        </div>
        <div class="footer-bottom">
            <span>© 2024 深圳无忧网络科技有限公司 版权所有</span>
            <span>
                <a href="#">隐私政策</a>
                <a href="#">服务条款</a>
                <a href="#">法律声明</a>
                <span>粤ICP备2024XXXXXXXX号</span>
            </span>
        </div>
    </footer>

    <script>
        (function() {
            // 移动端菜单
            const toggle = document.getElementById('menuToggle');
            const nav = document.getElementById('navMenu');
            if (toggle && nav) {
                toggle.addEventListener('click', () => nav.classList.toggle('mobile-open'));
                nav.querySelectorAll('a').forEach(link => {
                    link.addEventListener('click', () => nav.classList.remove('mobile-open'));
                });
            }

            // FAQ手风琴
            document.querySelectorAll('.faq-card').forEach(card => {
                const btn = card.querySelector('.faq-question');
                btn.addEventListener('click', () => {
                    const wasOpen = card.classList.contains('open');
                    // 关闭所有
                    document.querySelectorAll('.faq-card').forEach(c => c.classList.remove('open'));
                    if (!wasOpen) {
                        card.classList.add('open');
                    }
                });
            });

            // 导航高亮
            const sections = document.querySelectorAll('section[id]');
            const navLinks = document.querySelectorAll('.nav-links a:not(.btn-nav-download)');
            function setActiveLink() {
                let current = '';
                sections.forEach(sec => {
                    if (sec.getBoundingClientRect().top < 180) current = sec.id;
                });
                navLinks.forEach(link => {
                    link.classList.remove('link-active');
                    if (link.getAttribute('href') === '#' + current) link.classList.add('link-active');
                });
            }
            window.addEventListener('scroll', setActiveLink, { passive: true });
            setActiveLink();

            // 平滑滚动
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function(e) {
                    const id = this.getAttribute('href');
                    if (id === '#') return;
                    const target = document.querySelector(id);
                    if (target) {
                        e.preventDefault();
                        const offset = document.querySelector('.nav-container')?.offsetHeight || 68;
                        window.scrollTo({ top: target.offsetTop - offset - 8, behavior: 'smooth' });
                    }
                });
            });
           
        })();
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的GitHub项目</title>
    <style>
        :root {
            --primary: #0366d6;
            --dark: #24292e;
            --light: #f6f8fa;
            --border: #e1e4e8;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            line-height: 1.5;
            color: var(--dark);
            background-color: var(--light);
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem 1rem;
        }
        
        header {
            text-align: center;
            margin-bottom: 3rem;
            padding-bottom: 2rem;
            border-bottom: 1px solid var(--border);
        }
        
        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin: 0 auto 1rem;
            background-color: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            color: var(--primary);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .subtitle {
            font-size: 1.25rem;
            color: #586069;
            margin-bottom: 1.5rem;
        }
        
        .btn {
            display: inline-block;
            padding: 0.5rem 1rem;
            background-color: var(--primary);
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 500;
            transition: background-color 0.2s;
        }
        
        .btn:hover {
            background-color: #0356b6;
        }
        
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-bottom: 3rem;
        }
        
        .feature-card {
            background: white;
            border: 1px solid var(--border);
            border-radius: 6px;
            padding: 1.5rem;
            transition: transform 0.2s, box-shadow 0.2s;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        
        .feature-card h3 {
            margin-bottom: 0.75rem;
            color: var(--primary);
        }
        
        footer {
            text-align: center;
            padding: 2rem 0;
            color: #586069;
            border-top: 1px solid var(--border);
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 1rem;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .subtitle {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="avatar">👨‍💻</div>
            <h1>我的GitHub项目</h1>
            <p class="subtitle">一个简洁的开源项目展示页面</p>
            <a href="https://github.com/yourusername" class="btn">查看GitHub主页</a>
        </header>
        
        <section class="features">
            <div class="feature-card">
                <h3>项目一</h3>
                <p>项目一的简要描述，说明其主要功能和用途。</p>
            </div>
            
            <div class="feature-card">
                <h3>项目二</h3>
                <p>项目二的简要描述，说明其主要功能和用途。</p>
            </div>
            
            <div class="feature-card">
                <h3>项目三</h3>
                <p>项目三的简要描述，说明其主要功能和用途。</p>
            </div>
        </section>
        
        <footer>
            <p>© 2023 我的GitHub项目 | 使用MIT许可证</p>
        </footer>
    </div>
</body>
</html>

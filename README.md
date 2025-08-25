<h1 align="center">Welcome to Sperscintilla</h1>
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>黑曜石帮 - 为你实现一切不可能</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --main-bg-color: #0a0a14;
            --secondary-bg-color: #12121d;
            --accent-color: #00a2ff;
            --accent-glow: 0 0 10px var(--accent-color), 0 0 20px var(--accent-color);
            --text-color: #e0e0e0;
            --dark-text: #8a8a8a;
            --card-bg: rgba(25, 25, 35, 0.7);
            --border-radius: 8px;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, var(--main-bg-color), #000);
            color: var(--text-color);
            line-height: 1.6;
            overflow-x: hidden;
            background-attachment: fixed;
            min-height: 100vh;
            position: relative;
        }
        
        body::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(circle at 20% 30%, rgba(0, 162, 255, 0.15) 0%, transparent 40%),
                radial-gradient(circle at 80% 70%, rgba(0, 162, 255, 0.1) 0%, transparent 40%);
            z-index: -1;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            padding: 30px 0;
            position: relative;
            border-bottom: 1px solid rgba(0, 162, 255, 0.3);
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .logo-icon {
            width: 50px;
            height: 50px;
            background: var(--accent-color);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: var(--accent-glow);
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: 0 0 5px var(--accent-color); }
            50% { box-shadow: 0 0 20px var(--accent-color); }
            100% { box-shadow: 0 0 5px var(--accent-color); }
        }
        
        .logo-text {
            font-size: 2.2rem;
            font-weight: 700;
            background: linear-gradient(45deg, var(--accent-color), #00f7ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 10px rgba(0, 162, 255, 0.5);
        }
        
        .hero {
            text-align: center;
            padding: 80px 0 60px;
        }
        
        h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            background: linear-gradient(45deg, var(--accent-color), #00f7ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 15px rgba(0, 162, 255, 0.4);
        }
        
        .tagline {
            font-size: 1.5rem;
            margin-bottom: 30px;
            color: var(--dark-text);
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .cta-button {
            display: inline-block;
            padding: 12px 30px;
            background: transparent;
            color: var(--accent-color);
            border: 2px solid var(--accent-color);
            border-radius: 30px;
            font-size: 1.1rem;
            font-weight: 600;
            text-decoration: none;
            transition: all 0.3s ease;
            box-shadow: 0 0 10px rgba(0, 162, 255, 0.3);
            margin-top: 20px;
        }
        
        .cta-button:hover {
            background: var(--accent-color);
            color: #000;
            box-shadow: var(--accent-glow);
            transform: translateY(-3px);
        }
        
        section {
            padding: 60px 0;
        }
        
        h2 {
            font-size: 2.5rem;
            margin-bottom: 40px;
            text-align: center;
            position: relative;
            display: inline-block;
            left: 50%;
            transform: translateX(-50%);
        }
        
        h2::after {
            content: "";
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100%;
            height: 3px;
            background: var(--accent-color);
            box-shadow: var(--accent-glow);
        }
        
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, mgit init
git add index.html
git commit -m "初始提交，添加黑曜石帮主页"
git remote add origin https:// github.com/ Sperscintilla.git
git push -u origin master

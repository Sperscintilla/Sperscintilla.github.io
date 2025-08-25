<h1 align="center">Welcome to Sperscintilla</h1>
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>黑曜石团队 - 为你实现一切愿望</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0a0a1a 0%, #1a1a2e 100%);
            color: #fff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            overflow-x: hidden;
            padding: 20px;
            position: relative;
        }
        
        .container {
            max-width: 1200px;
            width: 100%;
            z-index: 10;
        }
        
        header {
            text-align: center;
            padding: 40px 20px;
            position: relative;
        }
        
        .logo {
            font-size: 5rem;
            color: #3498db;
            margin-bottom: 20px;
            text-shadow: 0 0 15px rgba(52, 152, 219, 0.5);
            animation: pulse 2s infinite;
        }
        
        h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            background: linear-gradient(to right, #3498db, #2ecc71);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }
        
        .tagline {
            font-size: 1.8rem;
            margin-bottom: 30px;
            color: #e0e0e0;
        }
        
        .welcome-text {
            background: rgba(0, 0, 0, 0.7);
            border-left: 5px solid #3498db;
            padding: 25px;
            font-size: 1.4rem;
            line-height: 1.6;
            margin: 30px auto;
            max-width: 800px;
            border-radius: 0 10px 10px 0;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
        }
        
        .contact-section {
            text-align: center;
            padding: 40px 20px;
            background: rgba(0, 0, 0, 0.6);
            border-radius: 15px;
            margin: 30px auto;
            max-width: 800px;
            box-shadow: 0 0 25px rgba(52, 152, 219, 0.3);
            border: 1px solid #3498db;
        }
        
        .contact-title {
            font-size: 2.2rem;
            margin-bottom: 25px;
            color: #3498db;
        }
        
        .contact-info {
            font-size: 1.8rem;
            margin: 20px 0;
            color: #e74c3c;
            text-shadow: 0 0 10px rgba(231, 76, 60, 0.3);
        }
        
        .contact-button {
            display: inline-block;
            background: linear-gradient(to right, #3498db, #2980b9);
            color: white;
            padding: 15px 40px;
            font-size: 1.4rem;
            text-decoration: none;
            border-radius: 50px;
            margin-top: 20px;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            border: none;
            cursor: pointer;
        }
        
        .contact-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
            background: linear-gradient(to right, #2980b9, #3498db);
        }
        
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 25px;
            margin: 50px 0;
        }
        
        .feature-card {
            background: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
            padding: 25px;
            width: 300px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
            border-top: 3px solid #3498db;
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 25px rgba(0, 0, 0, 0.4);
        }
        
        .feature-icon {
            font-size: 3rem;
            color: #3498db;
            margin-bottom: 20px;
        }
        
        .feature-title {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: #e0e0e0;
        }
        
        .feature-desc {
            font-size: 1.1rem;
            color: #b0b0b0;
            line-height: 1.5;
        }
        
        footer {
            text-align: center;
            padding: 30px;
            margin-top: 50px;
            color: #777;
            font-size: 1.1rem;
            border-top: 1px solid #222;
            width: 100%;
        }
        
        .particles {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
       

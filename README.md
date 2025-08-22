<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blogger Premium Theme - GitHub README</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            padding: 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        
        .github-readme {
            background-color: #161b22;
            border-radius: 6px;
            padding: 30px;
            margin: 20px 0;
            border: 1px solid #30363d;
        }
        
        .header {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 1px solid #30363d;
        }
        
        .logo {
            width: 50px;
            height: 50px;
            background: linear-gradient(135deg, #2ea44f, #1e6fbb);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            font-weight: bold;
            font-size: 22px;
        }
        
        h1 {
            color: #f0f6fc;
            font-size: 24px;
            font-weight: 600;
        }
        
        h2 {
            color: #f0f6fc;
            margin: 25px 0 15px 0;
            padding-bottom: 10px;
            border-bottom: 1px solid #30363d;
            font-size: 20px;
        }
        
        p {
            margin-bottom: 15px;
            font-size: 16px;
        }
        
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        
        .feature {
            background-color: #21262d;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 15px;
        }
        
        .feature h3 {
            color: #58a6ff;
            margin-bottom: 10px;
            font-size: 18px;
        }
        
        .telegram-cta {
            background: linear-gradient(135deg, #2ea44f 0%, #1e6fbb 100%);
            border-radius: 6px;
            padding: 20px;
            text-align: center;
            margin: 30px 0;
            border: 1px solid #30363d;
        }
        
        .telegram-cta h2 {
            color: white;
            border: none;
            margin-top: 0;
        }
        
        .telegram-button {
            display: inline-block;
            background-color: #0088cc;
            color: white;
            padding: 12px 25px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 15px;
            transition: background-color 0.3s;
        }
        
        .telegram-button:hover {
            background-color: #006da3;
        }
        
        .code-block {
            background-color: #21262d;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 16px;
            margin: 20px 0;
            overflow-x: auto;
            font-family: 'SFMono-Regular', Consolas, 'Liberation Mono', Menlo, monospace;
            font-size: 14px;
        }
        
        .code-comment {
            color: #8b949e;
        }
        
        .code-tag {
            color: #7ee787;
        }
        
        .code-attr {
            color: #79c0ff;
        }
        
        .code-string {
            color: #a5d6ff;
        }
        
        .note {
            background-color: #2b3139;
            border-left: 4px solid #3a7bd5;
            padding: 15px;
            margin: 20px 0;
            border-radius: 0 6px 6px 0;
        }
        
        .note h3 {
            color: #58a6ff;
            margin-bottom: 5px;
        }
        
        @media (max-width: 600px) {
            .features {
                grid-template-columns: 1fr;
            }
            
            body {
                padding: 10px;
            }
            
            .github-readme {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="github-readme">
        <div class="header">
            <div class="logo">BP</div>
            <h1>Blogger Premium Theme</h1>
        </div>
        
        <p>A modern, responsive, and feature-rich premium theme for Blogger platforms. This theme is designed to provide a professional look and optimal performance for your blog.</p>
        
        <h2>Features</h2>
        
        <div class="features">
            <div class="feature">
                <h3>Responsive Design</h3>
                <p>Looks great on all devices - desktop, tablet, and mobile.</p>
            </div>
            
            <div class="feature">
                <h3>SEO Optimized</h3>
                <p>Built with best SEO practices to help your content rank higher.</p>
            </div>
            
            <div class="feature">
                <h3>Fast Loading</h3>
                <p>Optimized for performance with minimal HTTP requests.</p>
            </div>
            
            <div class="feature">
                <h3>Customizable</h3>
                <p>Easy to customize colors, fonts, and layout without coding.</p>
            </div>
        </div>
        
        <h2>Installation</h2>
        
        <p>To install this theme on your Blogger blog:</p>
        
        <div class="code-block">
            <span class="code-comment"># Download the theme XML file</span><br>
            <span class="code-comment"># Go to Blogger Theme section</span><br>
            <span class="code-comment"># Click on "Backup/Restore"</span><br>
            <span class="code-comment"># Upload the XML file</span><br>
            <span class="code-comment"># Save changes</span>
        </div>
        
        <h2>Customization</h2>
        
        <p>You can easily customize the theme through Blogger's built-in template designer or by editing the CSS directly.</p>
        
        <div class="code-block">
            <span class="code-tag">&lt;Variable</span> <span class="code-attr">name</span>=<span class="code-string">"body.font"</span><br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="code-attr">description</span>=<span class="code-string">"Font"</span><br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="code-attr">type</span>=<span class="code-string">"font"</span><br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="code-attr">default</span>=<span class="code-string">"normal normal 16px 'Roboto', sans-serif"</span> <span class="code-tag">/&gt;</span>
        </div>
        
        <div class="telegram-cta">
            <h2>Get This Theme For Free!</h2>
            <p>Join our Telegram channel to download this premium theme for free and get regular updates with new templates.</p>
            <a href="https://t.me/ABDULLAHCODED" class="telegram-button">Join Telegram Channel</a>
        </div>
        
        <div class="note">
            <h3>Note</h3>
            <p>By joining our Telegram channel, you'll also get access to premium support, customization guides, and future updates.</p>
        </div>
        
        <h2>Support</h2>
        
        <p>If you have any questions or need help with customization, please contact us through our Telegram channel or create an issue in the GitHub repository.</p>
    </div>
</body>
</html>

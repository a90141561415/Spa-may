<!DOCTYPE.html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>舒壓按摩服務價目表</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Microsoft JhengHei', Arial, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #f5f1e6 0%, #ffffff 100%);
            color: #5a4a42;
            line-height: 1.6;
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            overflow: hidden;
        }
        
        .price-section {
            padding: 25px;
            border-bottom: 1px dashed #e0d6cf;
        }
        
        .price-section:last-child {
            border-bottom: none;
        }
        
        h2 {
            color: #7b655a;
            font-size: 1.6rem;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #f0e6df;
            display: flex;
            align-items: center;
        }
        
        h2 i {
            margin-right: 10px;
            font-size: 1.4rem;
        }
        
        .service-category {
            margin-bottom: 30px;
        }
        
        .service-item {
            display: flex;
            justify-content: space-between;
            padding: 12px 0;
            border-bottom: 1px dotted #e0d6cf;
        }
        
        .service-item:last-child {
            border-bottom: none;
        }
        
        .service-name {
            flex: 2;
            font-weight: 500;
        }
        
        .service-duration {
            flex: 1;
            color: #8d6e63;
            font-size: 0.95rem;
        }
        
        .service-price {
            flex: 1;
            text-align: right;
            font-weight: 600;
            color: #5d4037;
        }
        
        .highlight {
            background-color: #fff8f0;
            padding: 15px;
            border-radius: 8px;
            margin: 15px 0;
            border-left: 4px solid #ffab91;
        }
        
        .note {
            font-size: 0.9rem;
            color: #8d6e63;
            margin-top: 5px;
            font-style: italic;
        }
        
        .new-badge {
            background: #ff7043;
            color: white;
            font-size: 0.7rem;
            padding: 2px 8px;
            border-radius: 10px;
            margin-left: 8px;
            vertical-align: middle;
        }
        
        @media (max-width: 768px) {
            .service-item {
                flex-direction: column;
            }
            
            .service-duration, .service-price {
                margin-top: 5px;
                margin-left: 20px;
            }
            
            h1 {
                font-size: 1.8rem;
            }
        }
        
        .save-instructions {
            background: #e8f5e9;
            padding: 15px;
            border-radius: 8px;
            margin: 20px auto;
            max-width: 1000px;
            border-left: 4px solid #4caf50;
        }
        
        .save-instructions h3 {
            color: #2e7d32;
            margin-bottom: 10px;
        }
        
        .save-instructions ol {
            margin-left: 20px;
        }
        
        .save-instructions li {
            margin-bottom: 8px;
        }
        
        .save-instructions code {
            background: #f5f5f5;
            padding: 2px 6px;
            border-radius: 4px;
            font-family: monospace;
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>
<body>
    <div class="save-instructions">
        <h3>如何保存此價目表</h3>
        <ol>
            <li>按 <code>Ctrl+S</code> (Windows) 或 <code>Cmd+S</code> (Mac) 保存此頁面</li>
            <li>選擇保存位置，文件名為 <code>massage-price-list.html</code></li>
            <li>保存類型選擇"網頁，完整"或"HTML 文件"</li>
            <li>雙擊保存的文件即可在瀏覽器中打開</li>
        </ol>
    </div>
    
    <div class="container">
        <div class="price-section">
            <div class="service-category">
                <h2><i class="fas fa-spa"></i> 足部放鬆</h2>
                
                <div class="service-item">
                    <div class="service-name">基礎足部放鬆</div>
                    <div class="service-duration">60分鐘</div>
                    <div class="service-price">NT.700</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">足部放鬆</div>
                    <div class="service-duration">90分鐘</div>
                    <div class="service-price">NT.1150</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">足部放鬆</div>
                    <div class="service-duration">120分鐘</div>
                    <div class="service-price">NT.1400</div>
                </div>
            </div>
            
            <div class="service-category">
                <h2><i class="fas fa-concierge-bell"></i> 經絡套餐</h2>
                
                <div class="service-item">
                    <div class="service-name">足部+身體按摩</div>
                    <div class="service-duration">100分鐘</div>
                    <div class="service-price">NT.1450</div>
                </div>
            </div>
            
            <div class="service-category">
                <h2><i class="fas fa-hands"></i> 身體按摩</h2>
                
                <div class="service-item">
                    <div class="service-name">身體按摩</div>
                    <div class="service-duration">60分鐘</div>
                    <div class="service-price">NT.1000</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">身體按摩（指壓/油壓）</div>
                    <div class="service-duration">90分鐘</div>
                    <div class="service-price">NT.1450</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">身體按摩（指壓/油壓）</div>
                    <div class="service-duration">120分鐘</div>
                    <div class="service-price">NT.1900</div>
                </div>
            </div>
        </div>
        
        <div class="price-section">
            <div class="service-category">
                <h2><i class="fas fa-star"></i> 特色護理項目</h2>
                
                <div class="service-item">
                    <div class="service-name">肩頸刮痧舒壓</div>
                    <div class="service-duration">30分鐘</div>
                    <div class="service-price">NT.500</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">肩頸按摩放鬆</div>
                    <div class="service-duration">30分鐘</div>
                    <div class="service-price">NT.500</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">耳燭香薰減壓護理</div>
                    <div class="service-duration">40分鐘</div>
                    <div class="service-price">NT.800</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">香薰臍燭舒壓護理</div>
                    <div class="service-duration">30分鐘</div>
                    <div class="service-price">NT.950</div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">櫸木鬆筋護理</div>
                    <div class="service-duration">90分鐘</div>
                    <div class="service-price">NT.1700</div>
                </div>
            </div>
        </div>
        
        <div class="price-section">
            <div class="service-category">
                <h2><i class="fas fa-plus-circle"></i> 加購選項</h2>
                
                <div class="highlight">
                    <div class="service-item">
                        <div class="service-name">服務續時（足部）</div>
                        <div class="service-duration">每30分鐘</div>
                        <div class="service-price">NT.450</div>
                    </div>
                    <div class="service-item">
                        <div class="service-name">服務續時（身體）</div>
                        <div class="service-duration">每30分鐘</div>
                        <div class="service-price">NT.550</div>
                    </div>
                    <div class="service-item">
                        <div class="service-name">服務續時（櫸木鬆筋）</div>
                        <div class="service-duration">每30分鐘</div>
                        <div class="service-price">NT.650</div>
                    </div>
                    <div class="service-item">
                        <div class="service-name">升級多特瑞精油（足部）</div>
                        <div class="service-duration"></div>
                        <div class="service-price">NT.200</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    <div class="save-instructions">
        <h3>列印價目表</h3>
        <p>如需列印此價目表，請按 <code>Ctrl+P</code> (Windows) 或 <code>Cmd+P</code> (Mac)，然後選擇您的印表機。</p>
    </div>

    <script>
        // 添加簡單的互動效果
        document.querySelectorAll('.service-item').forEach(item => {
            item.addEventListener('click', function() {
                this.style.backgroundColor = '#f5f5f5';
                setTimeout(() => {
                    this.style.backgroundColor = '';
                }, 300);
            });
        });
        
        // 頁面載入完成後顯示提示
        window.addEventListener('load', function() {
            console.log('按摩價目表已載入完成！');
            console.log('請按Ctrl+S保存此頁面為HTML文件');
        });
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>小学生英语单词学习</title>
    <!-- 引入Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- 引入Font Awesome -->
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    
    <!-- 配置Tailwind自定义颜色和字体 -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#4F46E5', // 主色调：靛蓝色，代表知识和智慧
                        secondary: '#EC4899', // 辅助色：粉色，活泼有趣
                        accent: '#F59E0B', // 强调色：橙色，温暖有活力
                        neutral: '#F3F4F6', // 中性色：浅灰，背景
                    },
                    fontFamily: {
                        comic: ['Comic Sans MS', 'cursive', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    
    <!-- 自定义工具类 -->
    <style type="text/tailwindcss">
        @layer utilities {
            .content-auto {
                content-visibility: auto;
            }
            .card-shadow {
                box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);
            }
            .bounce-effect {
                transition: transform 0.3s ease;
            }
            .bounce-effect:hover {
                transform: translateY(-5px);
            }
            .touch-feedback {
                -webkit-tap-highlight-color: transparent;
            }
            .scale-on-touch {
                transition: transform 0.15s ease;
            }
            .scale-on-touch:active {
                transform: scale(0.95);
            }
        }
    </style>
</head>
<body class="bg-gradient-to-br from-blue-50 to-purple-50 min-h-screen font-comic touch-feedback">
    <!-- 顶部导航栏 -->
    <header class="bg-white shadow-md sticky top-0 z-50 transition-all duration-300">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fa fa-book text-primary text-2xl"></i>
                <h1 class="text-[clamp(1.25rem,5vw,2rem)] font-bold text-primary">英语单词小课堂</h1>
            </div>
            <div class="flex items-center space-x-3">
                <span id="progress-display" class="hidden md:inline-block bg-primary/10 text-primary px-3 py-1 rounded-full text-sm font-medium">
                    进度: <span id="progress-count">0</span>/<span id="total-words">0</span>
                </span>
                <button id="sound-toggle" class="p-2 rounded-full hover:bg-gray-100 transition-colors scale-on-touch">
                    <i class="fa fa-volume-up text-primary"></i>
                </button>
                <button id="help-btn" class="p-2 rounded-full hover:bg-gray-100 transition-colors scale-on-touch">
                    <i class="fa fa-question-circle text-primary"></i>
                </button>
                <button id="vocab-catalog-btn" class="p-2 rounded-full hover:bg-gray-100 transition-colors scale-on-touch">
                    <i class="fa fa-list text-primary"></i>
                </button>
            </div>
        </div>
    </header>

    <!-- 主内容区 -->
    <main class="container mx-auto px-4 py-6 md:py-8">
        <!-- 移动端进度条 -->
        <div class="md:hidden bg-white rounded-lg p-3 mb-4 shadow-sm">
            <div class="flex justify-between text-sm text-gray-600 mb-1">
                <span>学习进度</span>
                <span><span id="mobile-progress-count">0</span>/<span id="mobile-total-words">0</span></span>
            </div>
            <div class="w-full bg-gray-200 rounded-full h-2.5">
                <div id="progress-bar" class="bg-primary h-2.5 rounded-full" style="width: 0%"></div>
            </div>
        </div>
        
        <!-- 模式选择界面 -->
        <section id="mode-selection" class="max-w-2xl mx-auto">
            <div class="text-center mb-6 md:mb-10">
                <h2 class="text-[clamp(1.25rem,5vw,1.75rem)] font-bold text-gray-800 mb-3">选择学习模式</h2>
                <p class="text-gray-600">请选择你想要的学习方式，开始今天的单词学习吧！</p>
            </div>
            
            <div class="grid md:grid-cols-2 gap-4 md:gap-6">
                <!-- 英语到中文模式 -->
                <div class="bg-white rounded-2xl p-5 md:p-6 card-shadow bounce-effect cursor-pointer scale-on-touch" id="english-to-chinese-mode">
                    <div class="text-center">
                        <div class="w-14 h-14 md:w-16 md:h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-3 md:mb-4">
                            <i class="fa fa-language text-primary text-xl md:text-2xl"></i>
                        </div>
                        <h3 class="text-lg md:text-xl font-bold text-gray-800 mb-2">英语 → 中文</h3>
                        <p class="text-gray-600 text-xs md:text-sm">先学习英语单词，听发音，然后填写中文意思</p>
                        <button class="mt-3 md:mt-4 bg-primary text-white py-2 px-5 md:px-6 rounded-full hover:bg-primary/90 transition-colors scale-on-touch">
                            开始学习
                        </button>
                    </div>
                </div>
                
                <!-- 中文到英语模式 -->
                <div class="bg-white rounded-2xl p-5 md:p-6 card-shadow bounce-effect cursor-pointer scale-on-touch" id="chinese-to-english-mode">
                    <div class="text-center">
                        <div class="w-14 h-14 md:w-16 md:h-16 bg-secondary/10 rounded-full flex items-center justify-center mx-auto mb-3 md:mb-4">
                            <i class="fa fa-exchange text-secondary text-xl md:text-2xl"></i>
                        </div>
                        <h3 class="text-lg md:text-xl font-bold text-gray-800 mb-2">中文 → 英语</h3>
                        <p class="text-gray-600 text-xs md:text-sm">先学习中文意思，听英语发音，然后填写英语单词</p>
                        <button class="mt-3 md:mt-4 bg-secondary text-white py-2 px-5 md:px-6 rounded-full hover:bg-secondary/90 transition-colors scale-on-touch">
                            开始学习
                        </button>
                    </div>
                </div>
            </div>
            
            <!-- 单词列表选择 -->
            <div class="mt-6 md:mt-10 bg-white rounded-2xl p-5 md:p-6 card-shadow">
                <h3 class="text-lg md:text-xl font-bold text-gray-800 mb-3 md:mb-4 text-center">选择单词单元</h3>
                <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-2 md:gap-3">
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors active text-sm scale-on-touch" data-set="1">单元 1</button>
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors text-sm scale-on-touch" data-set="2">单元 2</button>
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors text-sm scale-on-touch" data-set="3">单元 3</button>
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors text-sm scale-on-touch" data-set="4">单元 4</button>
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors text-sm scale-on-touch" data-set="5">单元 5</button>
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors text-sm scale-on-touch" data-set="6">单元 6</button>
                </div>
                <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-2 md:gap-3 mt-2 md:mt-3">
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors text-sm scale-on-touch" data-set="7">单元 7</button>
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors text-sm scale-on-touch" data-set="8">单元 8</button>
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors text-sm scale-on-touch" data-set="9">单元 9</button>
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors text-sm scale-on-touch" data-set="10">单元 10</button>
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors text-sm scale-on-touch" data-set="11">单元 11</button>
                    <button class="vocab-set-btn bg-neutral hover:bg-primary/10 text-gray-800 py-2 px-2 md:px-3 rounded-lg transition-colors text-sm scale-on-touch" data-set="12">单元 12</button>
                </div>
            </div>
        </section>
        
        <!-- 学习界面 -->
        <section id="learning-area" class="max-w-2xl mx-auto hidden">
            <!-- 返回按钮 -->
            <button id="back-btn" class="flex items-center text-primary hover:text-primary/80 mb-4 md:mb-6 transition-colors scale-on-touch">
                <i class="fa fa-arrow-left mr-2"></i>
                <span>返回模式选择</span>
            </button>
            
            <!-- 单词卡片 -->
            <div class="bg-white rounded-2xl p-5 md:p-8 card-shadow mb-6 md:mb-8 transform transition-all duration-500">
                <div class="flex justify-between items-start mb-5 md:mb-6">
                    <span id="word-number" class="bg-primary/10 text-primary px-3 py-1 rounded-full text-sm font-medium">
                        单词 1/30
                    </span>
                    <button id="pronunciation-btn" class="bg-primary/10 hover:bg-primary/20 text-primary p-3 rounded-full transition-colors scale-on-touch">
                        <i class="fa fa-volume-up"></i>
                    </button>
                </div>
                
                <div class="text-center mb-6 md:mb-8">
                    <h3 id="word-display" class="text-[clamp(1.5rem,8vw,2.5rem)] font-bold text-gray-800 mb-2 transition-all duration-300">apple</h3>
                    <p id="phonetic-display" class="text-gray-500 italic text-base md:text-lg mb-3 md:mb-4">/ˈæpl/</p>
                    <p id="hint-text" class="text-gray-500 italic text-sm">点击喇叭图标听发音</p>
                </div>
                
                <!-- 输入区域 -->
                <div class="mb-5 md:mb-6">
                    <label for="answer-input" id="answer-label" class="block text-gray-700 mb-2 font-medium">请输入中文意思：</label>
                    <div class="flex">
                        <input type="text" id="answer-input" 
                            class="flex-1 px-4 py-3 border border-gray-300 rounded-l-lg focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary transition-all text-base"
                            placeholder="请在这里输入答案...">
                        <button id="submit-btn" class="bg-accent hover:bg-accent/90 text-white px-5 md:px-6 py-3 rounded-r-lg transition-colors scale-on-touch">
                            提交
                        </button>
                    </div>
                </div>
                
                <!-- 反馈区域 (默认隐藏) -->
                <div id="feedback-area" class="hidden">
                    <div id="correct-feedback" class="hidden bg-green-50 border border-green-200 text-green-700 px-4 py-3 rounded-lg">
                        <div class="flex items-start">
                            <i class="fa fa-check-circle text-green-500 mt-1 mr-3 text-xl"></i>
                            <div>
                                <h4 class="font-bold">太棒了！</h4>
                                <p>你的答案是正确的。</p>
                            </div>
                        </div>
                    </div>
                    
                    <div id="wrong-feedback" class="hidden bg-red-50 border border-red-200 text-red-700 px-4 py-3 rounded-lg">
                        <div class="flex items-start">
                            <i class="fa fa-times-circle text-red-500 mt-1 mr-3 text-xl"></i>
                            <div>
                                <h4 class="font-bold">再试一次！</h4>
                                <p>正确答案是：<span id="correct-answer" class="font-bold"></span></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- 导航按钮 -->
            <div class="flex justify-between">
                <button id="prev-btn" class="bg-gray-200 hover:bg-gray-300 text-gray-800 px-5 md:px-6 py-3 rounded-lg transition-colors disabled:opacity-50 disabled:cursor-not-allowed scale-on-touch" disabled>
                    <i class="fa fa-arrow-left mr-2"></i> 上一个
                </button>
                <button id="next-btn" class="bg-primary hover:bg-primary/90 text-white px-5 md:px-6 py-3 rounded-lg transition-colors scale-on-touch">
                    下一个 <i class="fa fa-arrow-right ml-2"></i>
                </button>
            </div>
        </section>
        
        <!-- 学习完成界面 -->
        <section id="completion-area" class="max-w-2xl mx-auto hidden text-center">
            <div class="bg-white rounded-2xl p-6 md:p-8 card-shadow">
                <div class="w-16 h-16 md:w-20 md:h-20 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-5 md:mb-6">
                    <i class="fa fa-trophy text-green-500 text-2xl md:text-3xl"></i>
                </div>
                
                <h2 class="text-[clamp(1.5rem,5vw,2rem)] font-bold text-gray-800 mb-3">恭喜你完成学习！</h2>
                <p class="text-gray-600 mb-5 md:mb-6">你已经完成了本次单词学习，真棒！</p>
                
                <div class="bg-neutral rounded-xl p-5 md:p-6 mb-6 md:mb-8">
                    <h3 class="text-lg font-bold text-gray-800 mb-3 md:mb-4">学习成果</h3>
                    <div class="flex justify-between items-center mb-2">
                        <span class="text-gray-700">总单词数：</span>
                        <span id="result-total" class="font-bold">30</span>
                    </div>
                    <div class="flex justify-between items-center mb-2">
                        <span class="text-gray-700">正确数：</span>
                        <span id="result-correct" class="font-bold text-green-600">0</span>
                    </div>
                    <div class="flex justify-between items-center">
                        <span class="text-gray-700">正确率：</span>
                        <span id="result-percentage" class="font-bold text-primary">0%</span>
                    </div>
                </div>
                
                <div class="flex flex-col sm:flex-row gap-3 md:gap-4 justify-center">
                    <button id="review-btn" class="bg-secondary hover:bg-secondary/90 text-white px-5 md:px-6 py-3 rounded-lg transition-colors scale-on-touch">
                        <i class="fa fa-refresh mr-2"></i> 重新学习
                    </button>
                    <button id="change-mode-btn" class="bg-primary hover:bg-primary/90 text-white px-5 md:px-6 py-3 rounded-lg transition-colors scale-on-touch">
                        <i class="fa fa-exchange mr-2"></i> 切换模式
                    </button>
                </div>
            </div>
        </section>
    </main>
    
    <!-- 帮助模态框 -->
    <div id="help-modal" class="fixed inset-0 bg-black/50 z-50 flex items-center justify-center hidden">
        <div class="bg-white rounded-2xl max-w-md w-full mx-4 p-5 md:p-6 relative">
            <button id="close-help" class="absolute top-4 right-4 text-gray-500 hover:text-gray-700 scale-on-touch">
                <i class="fa fa-times"></i>
            </button>
            <h3 class="text-xl font-bold text-gray-800 mb-4">使用帮助</h3>
            <div class="space-y-4 text-gray-600 text-sm md:text-base">
                <div>
                    <h4 class="font-bold text-gray-800 mb-1">选择学习模式</h4>
                    <p>英语→中文：学习英语单词，填写中文意思</p>
                    <p>中文→英语：学习中文意思，填写英语单词</p>
                </div>
                <div>
                    <h4 class="font-bold text-gray-800 mb-1">学习步骤</h4>
                    <p>1. 点击喇叭图标听单词发音</p>
                    <p>2. 在输入框中填写答案</p>
                    <p>3. 点击提交按钮检查答案</p>
                    <p>4. 点击上一个/下一个按钮浏览单词</p>
                </div>
                <div>
                    <h4 class="font-bold text-gray-800 mb-1">提示</h4>
                    <p>完成所有单词学习后，你可以查看自己的学习成果</p>
                </div>
            </div>
        </div>
    </div>
    
    <!-- 单元目录模态框 -->
    <div id="vocab-catalog-modal" class="fixed inset-0 bg-black/50 z-50 flex items-center justify-center hidden">
        <div class="bg-white rounded-2xl max-w-md w-full mx-4 p-5 md:p-6 relative max-h-[90vh] overflow-y-auto">
            <button id="close-catalog" class="absolute top-4 right-4 text-gray-500 hover:text-gray-700 scale-on-touch">
                <i class="fa fa-times"></i>
            </button>
            <h3 class="text-xl font-bold text-gray-800 mb-4">单词单元目录</h3>
            <div class="space-y-3 text-gray-600 text-sm md:text-base">
                <div class="flex justify-between p-2 border-b border-gray-100">
                    <span>单元 1</span>
                    <span class="text-gray-500 text-xs md:text-sm">基础水果和食物</span>
                </div>
                <div class="flex justify-between p-2 border-b border-gray-100">
                    <span>单元 2</span>
                    <span class="text-gray-500 text-xs md:text-sm">动物</span>
                </div>
                <div class="flex justify-between p-2 border-b border-gray-100">
                    <span>单元 3</span>
                    <span class="text-gray-500 text-xs md:text-sm">数字和颜色</span>
                </div>
                <div class="flex justify-between p-2 border-b border-gray-100">
                    <span>单元 4</span>
                    <span class="text-gray-500 text-xs md:text-sm">颜色和形状</span>
                </div>
                <div class="flex justify-between p-2 border-b border-gray-100">
                    <span>单元 5</span>
                    <span class="text-gray-500 text-xs md:text-sm">家庭成员和身体部位</span>
                </div>
                <div class="flex justify-between p-2 border-b border-gray-100">
                    <span>单元 6</span>
                    <span class="text-gray-500 text-xs md:text-sm">身体部位和衣物</span>
                </div>
                <div class="flex justify-between p-2 border-b border-gray-100">
                    <span>单元 7</span>
                    <span class="text-gray-500 text-xs md:text-sm">学校和学习用品</span>
                </div>
                <div class="flex justify-between p-2 border-b border-gray-100">
                    <span>单元 8</span>
                    <span class="text-gray-500 text-xs md:text-sm">动作和日常活动</span>
                </div>
                <div class="flex justify-between p-2 border-b border-gray-100">
                    <span>单元 9</span>
                    <span class="text-gray-500 text-xs md:text-sm">交通工具和地点</span>
                </div>
                <div class="flex justify-between p-2 border-b border-gray-100">
                    <span>单元 10</span>
                    <span class="text-gray-500 text-xs md:text-sm">时间和日期</span>
                </div>
                <div class="flex justify-between p-2 border-b border-gray-100">
                    <span>单元 11</span>
                    <span class="text-gray-500 text-xs md:text-sm">自然和天气</span>
                </div>
                <div class="flex justify-between p-2">
                    <span>单元 12</span>
                    <span class="text-gray-500 text-xs md:text-sm">形容词和副词</span>
                </div>
            </div>
        </div>
    </div>
    
    <!-- 页脚 -->
    <footer class="bg-white mt-8 md:mt-12 py-4 md:py-6 border-t">
        <div class="container mx-auto px-4 text-center text-gray-500 text-xs md:text-sm">
            <p>小学生英语单词学习 &copy; 2023</p>
            <p class="mt-1">让学习英语变得更有趣！</p>
        </div>
    </footer>

    <script>
        // 单词数据库 - 扩充至300词，涵盖小学教材常见词汇，分为12个单元，每单元25词
        const vocabularySets = {
            // 单元1：基础水果和食物
            1: [
                { english: "apple", chinese: "苹果", phonetic: "/ˈæpl/" },
                { english: "banana", chinese: "香蕉", phonetic: "/bəˈnɑːnə/" },
                { english: "orange", chinese: "橙子", phonetic: "/ˈɒrɪndʒ/" },
                { english: "grape", chinese: "葡萄", phonetic: "/ɡreɪp/" },
                { english: "pear", chinese: "梨", phonetic: "/peə/" },
                { english: "watermelon", chinese: "西瓜", phonetic: "/ˈwɔːtəmelən/" },
                { english: "strawberry", chinese: "草莓", phonetic: "/ˈstrɔːbəri/" },
                { english: "pineapple", chinese: "菠萝", phonetic: "/ˈpaɪnæpl/" },
                { english: "mango", chinese: "芒果", phonetic: "/ˈmæŋɡəʊ/" },
                { english: "peach", chinese: "桃子", phonetic: "/piːtʃ/" },
                { english: "cake", chinese: "蛋糕", phonetic: "/keɪk/" },
                { english: "bread", chinese: "面包", phonetic: "/bred/" },
                { english: "rice", chinese: "米饭", phonetic: "/raɪs/" },
                { english: "noodles", chinese: "面条", phonetic: "/ˈnuːdlz/" },
                { english: "egg", chinese: "鸡蛋", phonetic: "/eɡ/" },
                { english: "milk", chinese: "牛奶", phonetic: "/mɪlk/" },
                { english: "juice", chinese: "果汁", phonetic: "/dʒuːs/" },
                { english: "water", chinese: "水", phonetic: "/ˈwɔːtə/" },
                { english: "tea", chinese: "茶", phonetic: "/tiː/" },
                { english: "coffee", chinese: "咖啡", phonetic: "/ˈkɒfi/" },
                { english: "hamburger", chinese: "汉堡包", phonetic: "/ˈhæmbɜːɡə/" },
                { english: "hot dog", chinese: "热狗", phonetic: "/hɒt dɒɡ/" },
                { english: "chicken", chinese: "鸡肉", phonetic: "/ˈtʃɪkɪn/" },
                { english: "fish", chinese: "鱼", phonetic: "/fɪʃ/" },
                { english: "beef", chinese: "牛肉", phonetic: "/biːf/" }
            ],
            
            // 单元2：动物
            2: [
                { english: "dog", chinese: "狗", phonetic: "/dɒɡ/" },
                { english: "cat", chinese: "猫", phonetic: "/kæt/" },
                { english: "bird", chinese: "鸟", phonetic: "/bɜːd/" },
                { english: "fish", chinese: "鱼", phonetic: "/fɪʃ/" },
                { english: "rabbit", chinese: "兔子", phonetic: "/ˈræbɪt/" },
                { english: "hamster", chinese: "仓鼠", phonetic: "/ˈhæmstə/" },
                { english: "guinea pig", chinese: "豚鼠", phonetic: "/ˈɡɪni pɪɡ/" },
                { english: "turtle", chinese: "乌龟", phonetic: "/ˈtɜːtl/" },
                { english: "goldfish", chinese: "金鱼", phonetic: "/ˈɡəʊldfɪʃ/" },
                { english: "parrot", chinese: "鹦鹉", phonetic: "/ˈpærət/" },
                { english: "lion", chinese: "狮子", phonetic: "/ˈlaɪən/" },
                { english: "tiger", chinese: "老虎", phonetic: "/ˈtaɪɡə/" },
                { english: "elephant", chinese: "大象", phonetic: "/ˈelɪfənt/" },
                { english: "panda", chinese: "熊猫", phonetic: "/ˈpændə/" },
                { english: "monkey", chinese: "猴子", phonetic: "/ˈmʌŋki/" },
                { english: "giraffe", chinese: "长颈鹿", phonetic: "/dʒəˈrɑːf/" },
                { english: "zebra", chinese: "斑马", phonetic: "/ˈzebrə/" },
                { english: "bear", chinese: "熊", phonetic: "/beə/" },
                { english: "wolf", chinese: "狼", phonetic: "/wʊlf/" },
                { english: "fox", chinese: "狐狸", phonetic: "/fɒks/" },
                { english: "deer", chinese: "鹿", phonetic: "/dɪə/" },
                { english: "giraffe", chinese: "长颈鹿", phonetic: "/dʒəˈrɑːf/" },
                { english: "snake", chinese: "蛇", phonetic: "/sneɪk/" },
                { english: "frog", chinese: "青蛙", phonetic: "/frɒɡ/" },
                { english: "butterfly", chinese: "蝴蝶", phonetic: "/ˈbʌtəflaɪ/" }
            ],
            
            // 单元3：数字和颜色
            3: [
                { english: "one", chinese: "一", phonetic: "/wʌn/" },
                { english: "two", chinese: "二", phonetic: "/tuː/" },
                { english: "three", chinese: "三", phonetic: "/θriː/" },
                { english: "four", chinese: "四", phonetic: "/fɔː/" },
                { english: "five", chinese: "五", phonetic: "/faɪv/" },
                { english: "six", chinese: "六", phonetic: "/sɪks/" },
                { english: "seven", chinese: "七", phonetic: "/ˈsevn/" },
                { english: "eight", chinese: "八", phonetic: "/eɪt/" },
                { english: "nine", chinese: "九", phonetic: "/naɪn/" },
                { english: "ten", chinese: "十", phonetic: "/ten/" },
                { english: "eleven", chinese: "十一", phonetic: "/ɪˈlevn/" },
                { english: "twelve", chinese: "十二", phonetic: "/twelv/" },
                { english: "thirteen", chinese: "十三", phonetic: "/ˌθɜːˈtiːn/" },
                { english: "fourteen", chinese: "十四", phonetic: "/ˌfɔːˈtiːn/" },
                { english: "fifteen", chinese: "十五", phonetic: "/ˌfɪfˈtiːn/" },
                { english: "sixteen", chinese: "十六", phonetic: "/ˌsɪksˈtiːn/" },
                { english: "seventeen", chinese: "十七", phonetic: "/ˌsevnˈtiːn/" },
                { english: "eighteen", chinese: "十八", phonetic: "/ˌeɪˈtiːn/" },
                { english: "nineteen", chinese: "十九", phonetic: "/ˌnaɪnˈtiːn/" },
                { english: "twenty", chinese: "二十", phonetic: "/ˈtwenti/" },
                { english: "red", chinese: "红色", phonetic: "/red/" },
                { english: "blue", chinese: "蓝色", phonetic: "/bluː/" },
                { english: "yellow", chinese: "黄色", phonetic: "/ˈjeləʊ/" },
                { english: "green", chinese: "绿色", phonetic: "/ɡriːn/" },
                { english: "black", chinese: "黑色", phonetic: "/blæk/" }
            ],
            
            // 单元4：颜色和形状
            4: [
                { english: "white", chinese: "白色", phonetic: "/waɪt/" },
                { english: "pink", chinese: "粉色", phonetic: "/pɪŋk/" },
                { english: "purple", chinese: "紫色", phonetic: "/ˈpɜːpl/" },
                { english: "orange", chinese: "橙色", phonetic: "/ˈɒrɪndʒ/" },
                { english: "brown", chinese: "棕色", phonetic: "/braʊn/" },
                { english: "gray", chinese: "灰色", phonetic: "/ɡreɪ/" },
                { english: "gold", chinese: "金色", phonetic: "/ɡəʊld/" },
                { english: "silver", chinese: "银色", phonetic: "/ˈsɪlvə/" },
                { english: "rainbow", chinese: "彩虹", phonetic: "/ˈreɪnbəʊ/" },
                { english: "color", chinese: "颜色", phonetic: "/ˈkʌlə/" },
                { english: "shape", chinese: "形状", phonetic: "/ʃeɪp/" },
                { english: "circle", chinese: "圆形", phonetic: "/ˈsɜːkl/" },
                { english: "square", chinese: "正方形", phonetic: "/skweə/" },
                { english: "triangle", chinese: "三角形", phonetic: "/ˈtraɪæŋɡl/" },
                { english: "rectangle", chinese: "长方形", phonetic: "/ˈrektæŋɡl/" },
                { english: "oval", chinese: "椭圆形", phonetic: "/ˈəʊvl/" },
                { english: "star", chinese: "星形", phonetic: "/stɑː/" },
                { english: "heart", chinese: "心形", phonetic: "/hɑːt/" },
                { english: "diamond", chinese: "菱形", phonetic: "/ˈdaɪəmənd/" },
                { english: "crescent", chinese: "月牙形", phonetic: "/ˈkresnt/" },
                { english: "round", chinese: "圆的", phonetic: "/raʊnd/" },
                { english: "straight", chinese: "直的", phonetic: "/streɪt/" },
                { english: "curved", chinese: "弯曲的", phonetic: "/kɜːvd/" },
                { english: "big", chinese: "大的", phonetic: "/bɪɡ/" },
                { english: "small", chinese: "小的", phonetic: "/smɔːl/" }
            ],
            
            // 单元5：家庭成员和身体部位
            5: [
                { english: "father", chinese: "父亲", phonetic: "/ˈfɑːðə/" },
                { english: "mother", chinese: "母亲", phonetic: "/ˈmʌðə/" },
                { english: "brother", chinese: "兄弟", phonetic: "/ˈbrʌðə/" },
                { english: "sister", chinese: "姐妹", phonetic: "/ˈsɪstə/" },
                { english: "grandfather", chinese: "祖父", phonetic: "/ˈɡrænfɑːðə/" },
                { english: "grandmother", chinese: "祖母", phonetic: "/ˈɡrænmʌðə/" },
                { english: "uncle", chinese: "叔叔", phonetic: "/ˈʌŋkl/" },
                { english: "aunt", chinese: "阿姨", phonetic: "/ɑːnt/" },
                { english: "cousin", chinese: "表兄弟姐妹", phonetic: "/ˈkʌzn/" },
                { english: "son", chinese: "儿子", phonetic: "/sʌn/" },
                { english: "daughter", chinese: "女儿", phonetic: "/ˈdɔːtə/" },
                { english: "family", chinese: "家庭", phonetic: "/ˈfæməli/" },
                { english: "head", chinese: "头", phonetic: "/hed/" },
                { english: "hair", chinese: "头发", phonetic: "/heə/" },
                { english: "face", chinese: "脸", phonetic: "/feɪs/" },
                { english: "eye", chinese: "眼睛", phonetic: "/aɪ/" },
                { english: "nose", chinese: "鼻子", phonetic: "/nəʊz/" },
                { english: "mouth", chinese: "嘴", phonetic: "/maʊθ/" },
                { english: "tooth", chinese: "牙齿", phonetic: "/tuːθ/" },
                { english: "ear", chinese: "耳朵", phonetic: "/ɪə/" },
                { english: "neck", chinese: "脖子", phonetic: "/nek/" },
                { english: "shoulder", chinese: "肩膀", phonetic: "/ˈʃəʊldə/" },
                { english: "arm", chinese: "胳膊", phonetic: "/ɑːm/" },
                { english: "hand", chinese: "手", phonetic: "/hænd/" },
                { english: "finger", chinese: "手指", phonetic: "/ˈfɪŋɡə/" }
            ],
            
            // 单元6：身体部位和衣物
            6: [
                { english: "leg", chinese: "腿", phonetic: "/leɡ/" },
                { english: "knee", chinese: "膝盖", phonetic: "/niː/" },
                { english: "foot", chinese: "脚", phonetic: "/fʊt/" },
                { english: "toe", chinese: "脚趾", phonetic: "/təʊ/" },
                { english: "body", chinese: "身体", phonetic: "/ˈbɒdi/" },
                { english: "back", chinese: "背部", phonetic: "/bæk/" },
                { english: "stomach", chinese: "肚子", phonetic: "/ˈstʌmək/" },
                { english: "heart", chinese: "心脏", phonetic: "/hɑːt/" },
                { english: "lung", chinese: "肺", phonetic: "/lʌŋ/" },
                { english: "liver", chinese: "肝脏", phonetic: "/ˈlɪvə/" },
                { english: "clothes", chinese: "衣服", phonetic: "/kləʊðz/" },
                { english: "shirt", chinese: "衬衫", phonetic: "/ʃɜːt/" },
                { english: "T-shirt", chinese: "T恤衫", phonetic: "/ˈtiː ʃɜːt/" },
                { english: "pants", chinese: "裤子", phonetic: "/pænts/" },
                { english: "skirt", chinese: "裙子", phonetic: "/skɜːt/" },
                { english: "dress", chinese: "连衣裙", phonetic: "/dres/" },
                { english: "coat", chinese: "外套", phonetic: "/kəʊt/" },
                { english: "sweater", chinese: "毛衣", phonetic: "/ˈswetə/" },
                { english: "jacket", chinese: "夹克", phonetic: "/ˈdʒækɪt/" },
                { english: "hat", chinese: "帽子", phonetic: "/hæt/" },
                { english: "cap", chinese: "棒球帽", phonetic: "/kæp/" },
                { english: "shoe", chinese: "鞋子", phonetic: "/ʃuː/" },
                { english: "sock", chinese: "袜子", phonetic: "/sɒk/" },
                { english: "glove", chinese: "手套", phonetic: "/ɡlʌv/" },
                { english: "scarf", chinese: "围巾", phonetic: "/skɑːf/" }
            ],
            
            // 单元7：学校和学习用品
            7: [
                { english: "school", chinese: "学校", phonetic: "/skuːl/" },
                { english: "classroom", chinese: "教室", phonetic: "/ˈklɑːsruːm/" },
                { english: "teacher", chinese: "老师", phonetic: "/ˈtiːtʃə/" },
                { english: "student", chinese: "学生", phonetic: "/ˈstjuːdnt/" },
                { english: "pupil", chinese: "小学生", phonetic: "/ˈpjuːpl/" },
                { english: "classmate", chinese: "同学", phonetic: "/ˈklɑːsmeɪt/" },
                { english: "desk", chinese: "课桌", phonetic: "/desk/" },
                { english: "chair", chinese: "椅子", phonetic: "/tʃeə/" },
                { english: "blackboard", chinese: "黑板", phonetic: "/ˈblækbɔːd/" },
                { english: "whiteboard", chinese: "白板", phonetic: "/ˈwaɪtbɔːd/" },
                { english: "book", chinese: "书", phonetic: "/bʊk/" },
                { english: "notebook", chinese: "笔记本", phonetic: "/ˈnəʊtbʊk/" },
                { english: "pen", chinese: "钢笔", phonetic: "/pen/" },
                { english: "pencil", chinese: "铅笔", phonetic: "/ˈpensl/" },
                { english: "eraser", chinese: "橡皮", phonetic: "/ɪˈreɪzə/" },
                { english: "ruler", chinese: "尺子", phonetic: "/ˈruːlə/" },
                { english: "pencil case", chinese: "铅笔盒", phonetic: "/ˈpensl keɪs/" },
                { english: "backpack", chinese: "书包", phonetic: "/ˈbækpæk/" },
                { english: "crayon", chinese: "蜡笔", phonetic: "/ˈkreɪən/" },
                { english: "marker", chinese: "马克笔", phonetic: "/ˈmɑːkə/" },
                { english: "scissors", chinese: "剪刀", phonetic: "/ˈsɪzəz/" },
                { english: "glue", chinese: "胶水", phonetic: "/ɡluː/" },
                { english: "paper", chinese: "纸", phonetic: "/ˈpeɪpə/" },
                { english: "dictionary", chinese: "字典", phonetic: "/ˈdɪkʃənri/" },
                { english: "map", chinese: "地图", phonetic: "/mæp/" }
            ],
            
            // 单元8：动作和日常活动
            8: [
                { english: "run", chinese: "跑", phonetic: "/rʌn/" },
                { english: "walk", chinese: "走", phonetic: "/wɔːk/" },
                { english: "jump", chinese: "跳", phonetic: "/dʒʌmp/" },
                { english: "swim", chinese: "游泳", phonetic: "/swɪm/" },
                { english: "fly", chinese: "飞", phonetic: "/flaɪ/" },
                { english: "eat", chinese: "吃", phonetic: "/iːt/" },
                { english: "drink", chinese: "喝", phonetic: "/drɪŋk/" },
                { english: "sleep", chinese: "睡觉", phonetic: "/sliːp/" },
                { english: "wake", chinese: "醒来", phonetic: "/weɪk/" },
                { english: "read", chinese: "读", phonetic: "/riːd/" },
                { english: "write", chinese: "写", phonetic: "/raɪt/" },
                { english: "draw", chinese: "画", phonetic: "/drɔː/" },
                { english: "sing", chinese: "唱", phonetic: "/sɪŋ/" },
                { english: "dance", chinese: "跳舞", phonetic: "/dɑːns/" },
                { english: "play", chinese: "玩", phonetic: "/pleɪ/" },
                { english: "study", chinese: "学习", phonetic: "/ˈstʌdi/" },
                { english: "teach", chinese: "教", phonetic: "/tiːtʃ/" },
                { english: "learn", chinese: "学", phonetic: "/lɜːn/" },
                { english: "listen", chinese: "听", phonetic: "/ˈlɪsn/" },
                { english: "speak", chinese: "说", phonetic: "/spiːk/" },
                { english: "watch", chinese: "看", phonetic: "/wɒtʃ/" },
                { english: "hear", chinese: "听见", phonetic: "/hɪə/" },
                { english: "see", chinese: "看见", phonetic: "/siː/" },
                { english: "think", chinese: "想", phonetic: "/θɪŋk/" },
                { english: "do", chinese: "做", phonetic: "/duː/" }
            ],
            
            // 单元9：交通工具和地点
            9: [
                { english: "car", chinese: "小汽车", phonetic: "/kɑː/" },
                { english: "bus", chinese: "公共汽车", phonetic: "/bʌs/" },
                { english: "bike", chinese: "自行车", phonetic: "/baɪk/" },
                { english: "bicycle", chinese: "自行车", phonetic: "/ˈbaɪsɪkl/" },
                { english: "train", chinese: "火车", phonetic: "/treɪn/" },
                { english: "plane", chinese: "飞机", phonetic: "/pleɪn/" },
                { english: "ship", chinese: "轮船", phonetic: "/ʃɪp/" },
                { english: "boat", chinese: "小船", phonetic: "/bəʊt/" },
                { english: "taxi", chinese: "出租车", phonetic: "/ˈtæksi/" },
                { english: "truck", chinese: "卡车", phonetic: "/trʌk/" },
                { english: "motorcycle", chinese: "摩托车", phonetic: "/ˈməʊtəsaɪkl/" },
                { english: "ambulance", chinese: "救护车", phonetic: "/ˈæmbjələns/" },
                { english: "fire truck", chinese: "消防车", phonetic: "/ˈfaɪə trʌk/" },
                { english: "police car", chinese: "警车", phonetic: "/pəˈliːs kɑː/" },
                { english: "subway", chinese: "地铁", phonetic: "/ˈsʌbweɪ/" },
                { english: "station", chinese: "车站", phonetic: "/ˈsteɪʃn/" },
                { english: "airport", chinese: "机场", phonetic: "/ˈeəpɔːt/" },
                { english: "hospital", chinese: "医院", phonetic: "/ˈhɒspɪtl/" },
                { english: "school", chinese: "学校", phonetic: "/skuːl/" },
                { english: "park", chinese: "公园", phonetic: "/pɑːk/" },
                { english: "zoo", chinese: "动物园", phonetic: "/zuː/" },
                { english: "library", chinese: "图书馆", phonetic: "/ˈlaɪbrəri/" },
                { english: "supermarket", chinese: "超市", phonetic: "/ˈsuːpəmɑːkɪt/" },
                { english: "restaurant", chinese: "餐馆", phonetic: "/ˈrestrɒnt/" },
                { english: "bank", chinese: "银行", phonetic: "/bæŋk/" }
            ],
            
            // 单元10：时间和日期
            10: [
                { english: "time", chinese: "时间", phonetic: "/taɪm/" },
                { english: "clock", chinese: "时钟", phonetic: "/klɒk/" },
                { english: "watch", chinese: "手表", phonetic: "/wɒtʃ/" },
                { english: "hour", chinese: "小时", phonetic: "/ˈaʊə/" },
                { english: "minute", chinese: "分钟", phonetic: "/ˈmɪnɪt/" },
                { english: "second", chinese: "秒", phonetic: "/ˈsekənd/" },
                { english: "morning", chinese: "早上", phonetic: "/ˈmɔːnɪŋ/" },
                { english: "afternoon", chinese: "下午", phonetic: "/ˌɑːftəˈnuːn/" },
                { english: "evening", chinese: "晚上", phonetic: "/ˈiːvnɪŋ/" },
                { english: "night", chinese: "夜晚", phonetic: "/naɪt/" },
                { english: "day", chinese: "天", phonetic: "/deɪ/" },
                { english: "week", chinese: "星期", phonetic: "/wiːk/" },
                { english: "month", chinese: "月", phonetic: "/mʌnθ/" },
                { english: "year", chinese: "年", phonetic: "/jɪə/" },
                { english: "Monday", chinese: "星期一", phonetic: "/ˈmʌndeɪ/" },
                { english: "Tuesday", chinese: "星期二", phonetic: "/ˈtjuːzdeɪ/" },
                { english: "Wednesday", chinese: "星期三", phonetic: "/ˈwenzdeɪ/" },
                { english: "Thursday", chinese: "星期四", phonetic: "/ˈθɜːzdeɪ/" },
                { english: "Friday", chinese: "星期五", phonetic: "/ˈfraɪdeɪ/" },
                { english: "Saturday", chinese: "星期六", phonetic: "/ˈsætədeɪ/" },
                { english: "Sunday", chinese: "星期日", phonetic: "/ˈsʌndeɪ/" },
                { english: "today", chinese: "今天", phonetic: "/təˈdeɪ/" },
                { english: "tomorrow", chinese: "明天", phonetic: "/təˈmɒrəʊ/" },
                { english: "yesterday", chinese: "昨天", phonetic: "/ˈjestədeɪ/" },
                { english: "now", chinese: "现在", phonetic: "/naʊ/" }
            ],
            
            // 单元11：自然和天气
            11: [
                { english: "sky", chinese: "天空", phonetic: "/skaɪ/" },
                { english: "sun", chinese: "太阳", phonetic: "/sʌn/" },
                { english: "moon", chinese: "月亮", phonetic: "/muːn/" },
                { english: "star", chinese: "星星", phonetic: "/stɑː/" },
                { english: "cloud", chinese: "云", phonetic: "/klaʊd/" },
                { english: "rain", chinese: "雨", phonetic: "/reɪn/" },
                { english: "snow", chinese: "雪", phonetic: "/snəʊ/" },
                { english: "wind", chinese: "风", phonetic: "/wɪnd/" },
                { english: "thunder", chinese: "雷", phonetic: "/ˈθʌndə/" },
                { english: "lightning", chinese: "闪电", phonetic: "/ˈlaɪtnɪŋ/" },
                { english: "rainbow", chinese: "彩虹", phonetic: "/ˈreɪnbəʊ/" },
                { english: "weather", chinese: "天气", phonetic: "/ˈweðə/" },
                { english: "hot", chinese: "热的", phonetic: "/hɒt/" },
                { english: "cold", chinese: "冷的", phonetic: "/kəʊld/" },
                { english: "warm", chinese: "温暖的", phonetic: "/wɔːm/" },
                { english: "cool", chinese: "凉爽的", phonetic: "/kuːl/" },
                { english: "sunny", chinese: "晴朗的", phonetic: "/ˈsʌni/" },
                { english: "cloudy", chinese: "多云的", phonetic: "/ˈklaʊdi/" },
                { english: "rainy", chinese: "下雨的", phonetic: "/ˈreɪni/" },
                { english: "snowy", chinese: "下雪的", phonetic: "/ˈsnəʊi/" },
                { english: "windy", chinese: "刮风的", phonetic: "/ˈwɪndi/" },
                { english: "foggy", chinese: "有雾的", phonetic: "/ˈfɒɡi/" },
                { english: "earth", chinese: "地球", phonetic: "/ɜːθ/" },
                { english: "mountain", chinese: "山", phonetic: "/ˈmaʊntən/" },
                { english: "river", chinese: "河", phonetic: "/ˈrɪvə/" }
            ],
            
            // 单元12：形容词和副词
            12: [
                { english: "happy", chinese: "开心的", phonetic: "/ˈhæpi/" },
                { english: "sad", chinese: "难过的", phonetic: "/sæd/" },
                { english: "angry", chinese: "生气的", phonetic: "/ˈæŋɡri/" },
                { english: "scared", chinese: "害怕的", phonetic: "/skeəd/" },
                { english: "excited", chinese: "兴奋的", phonetic: "/ɪkˈsaɪtɪd/" },
                { english: "tired", chinese: "累的", phonetic: "/ˈtaɪəd/" },
                { english: "hungry", chinese: "饿的", phonetic: "/ˈhʌŋɡri/" },
                { english: "thirsty", chinese: "渴的", phonetic: "/ˈθɜːsti/" },
                { english: "good", chinese: "好的", phonetic: "/ɡʊd/" },
                { english: "bad", chinese: "坏的", phonetic: "/bæd/" },
                { english: "new", chinese: "新的", phonetic: "/njuː/" },
                { english: "old", chinese: "旧的", phonetic: "/əʊld/" },
                { english: "big", chinese: "大的", phonetic: "/bɪɡ/" },
                { english: "small", chinese: "小的", phonetic: "/smɔːl/" },
                { english: "long", chinese: "长的", phonetic: "/lɒŋ/" },
                { english: "short", chinese: "短的", phonetic: "/ʃɔːt/" },
                { english: "tall", chinese: "高的", phonetic: "/tɔːl/" },
                { english: "short", chinese: "矮的", phonetic: "/ʃɔːt/" },
                { english: "fat", chinese: "胖的", phonetic: "/fæt/" },
                { english: "thin", chinese: "瘦的", phonetic: "/θɪn/" },
                { english: "fast", chinese: "快的", phonetic: "/fɑːst/" },
                { english: "slow", chinese: "慢的", phonetic: "/sləʊ/" },
                { english: "quickly", chinese: "快速地", phonetic: "/ˈkwɪkli/" },
                { english: "slowly", chinese: "慢慢地", phonetic: "/ˈsləʊli/" },
                { english: "beautifully", chinese: "漂亮地", phonetic: "/ˈbjuːtɪfli/" }
            ]
        };

        // 全局状态
        let currentMode = null; // 'english-to-chinese' 或 'chinese-to-english'
        let currentSet = 1;
        let currentVocabulary = vocabularySets[1];
        let currentIndex = 0;
        let userAnswers = [];
        let soundEnabled = true;

        // DOM 元素
        const modeSelection = document.getElementById('mode-selection');
        const learningArea = document.getElementById('learning-area');
        const completionArea = document.getElementById('completion-area');
        const englishToChineseMode = document.getElementById('english-to-chinese-mode');
        const chineseToEnglishMode = document.getElementById('chinese-to-english-mode');
        const vocabSetBtns = document.querySelectorAll('.vocab-set-btn');
        const backBtn = document.getElementById('back-btn');
        const wordDisplay = document.getElementById('word-display');
        const phoneticDisplay = document.getElementById('phonetic-display');
        const answerLabel = document.getElementById('answer-label');
        const answerInput = document.getElementById('answer-input');
        const submitBtn = document.getElementById('submit-btn');
        const feedbackArea = document.getElementById('feedback-area');
        const correctFeedback = document.getElementById('correct-feedback');
        const wrongFeedback = document.getElementById('wrong-feedback');
        const correctAnswer = document.getElementById('correct-answer');
        const prevBtn = document.getElementById('prev-btn');
        const nextBtn = document.getElementById('next-btn');
        const wordNumber = document.getElementById('word-number');
        const pronunciationBtn = document.getElementById('pronunciation-btn');
        const progressCount = document.getElementById('progress-count');
        const totalWords = document.getElementById('total-words');
        const mobileProgressCount = document.getElementById('mobile-progress-count');
        const mobileTotalWords = document.getElementById('mobile-total-words');
        const progressBar = document.getElementById('progress-bar');
        const reviewBtn = document.getElementById('review-btn');
        const changeModeBtn = document.getElementById('change-mode-btn');
        const resultTotal = document.getElementById('result-total');
        const resultCorrect = document.getElementById('result-correct');
        const resultPercentage = document.getElementById('result-percentage');
        const helpBtn = document.getElementById('help-btn');
        const helpModal = document.getElementById('help-modal');
        const closeHelp = document.getElementById('close-help');
        const soundToggle = document.getElementById('sound-toggle');
        const vocabCatalogBtn = document.getElementById('vocab-catalog-btn');
        const vocabCatalogModal = document.getElementById('vocab-catalog-modal');
        const closeCatalog = document.getElementById('close-catalog');

        // 初始化
        function init() {
            // 设置事件监听器
            englishToChineseMode.addEventListener('click', () => startLearning('english-to-chinese'));
            chineseToEnglishMode.addEventListener('click', () => startLearning('chinese-to-english'));
            
            vocabSetBtns.forEach(btn => {
                btn.addEventListener('click', () => {
                    // 更新UI
                    vocabSetBtns.forEach(b => {
                        b.classList.remove('active', 'bg-primary/10', 'text-primary');
                        b.classList.add('bg-neutral', 'text-gray-800');
                    });
                    btn.classList.remove('bg-neutral', 'text-gray-800');
                    btn.classList.add('active', 'bg-primary/10', 'text-primary');
                    
                    // 更新当前词汇集
                    currentSet = parseInt(btn.dataset.set);
                    currentVocabulary = vocabularySets[currentSet];
                    updateProgressDisplay();
                });
            });
            
            backBtn.addEventListener('click', showModeSelection);
            submitBtn.addEventListener('click', checkAnswer);
            prevBtn.addEventListener('click', goToPreviousWord);
            nextBtn.addEventListener('click', goToNextWord);
            pronunciationBtn.addEventListener('click', playPronunciation);
            reviewBtn.addEventListener('click', restartLearning);
            changeModeBtn.addEventListener('click', switchMode);
            helpBtn.addEventListener('click', () => helpModal.classList.remove('hidden'));
            closeHelp.addEventListener('click', () => helpModal.classList.add('hidden'));
            soundToggle.addEventListener('click', toggleSound);
            
            // 单元目录按钮事件
            vocabCatalogBtn.addEventListener('click', () => vocabCatalogModal.classList.remove('hidden'));
            closeCatalog.addEventListener('click', () => vocabCatalogModal.classList.add('hidden'));
            
            // 点击模态框外部关闭
            helpModal.addEventListener('click', (e) => {
                if (e.target === helpModal) {
                    helpModal.classList.add('hidden');
                }
            });
            
            vocabCatalogModal.addEventListener('click', (e) => {
                if (e.target === vocabCatalogModal) {
                    vocabCatalogModal.classList.add('hidden');
                }
            });
            
            // 键盘事件
            answerInput.addEventListener('keypress', (e) => {
                if (e.key === 'Enter') {
                    checkAnswer();
                }
            });
            
            // 触摸优化 - 输入框聚焦时调整视图
            answerInput.addEventListener('focus', () => {
                if (window.innerWidth < 768) {
                    setTimeout(() => {
                        window.scrollTo({ top: 150, behavior: 'smooth' });
                    }, 300);
                }
            });
            
            // 初始化进度显示
            totalWords.textContent = currentVocabulary.length;
            mobileTotalWords.textContent = currentVocabulary.length;
            updateProgressDisplay();
            
            // 窗口大小变化时重新调整
            window.addEventListener('resize', adjustLayoutForScreenSize);
        }

        // 根据屏幕尺寸调整布局
        function adjustLayoutForScreenSize() {
            // 在小屏幕上如果输入框处于焦点，调整滚动位置
            if (window.innerWidth < 768 && document.activeElement === answerInput) {
                window.scrollTo({ top: 150, behavior: 'smooth' });
            }
        }

        // 开始学习
        function startLearning(mode) {
            currentMode = mode;
            currentIndex = 0;
            userAnswers = new Array(currentVocabulary.length).fill(null);
            
            // 更新UI
            modeSelection.classList.add('hidden');
            learningArea.classList.remove('hidden');
            completionArea.classList.add('hidden');
            
            // 显示第一个单词
            displayCurrentWord();
        }

        // 返回模式选择
        function showModeSelection() {
            modeSelection.classList.remove('hidden');
            learningArea.classList.add('hidden');
            completionArea.classList.add('hidden');
        }

        // 显示当前单词
        function displayCurrentWord() {
            const word = currentVocabulary[currentIndex];
            
            // 根据模式显示不同内容
            if (currentMode === 'english-to-chinese') {
                wordDisplay.textContent = word.english;
                phoneticDisplay.textContent = word.phonetic;
                answerLabel.textContent = '请输入中文意思：';
            } else {
                wordDisplay.textContent = word.chinese;
                phoneticDisplay.textContent = word.phonetic;
                answerLabel.textContent = '请输入英语单词：';
            }
            
            // 更新单词编号
            wordNumber.textContent = `单词 ${currentIndex + 1}/${currentVocabulary.length}`;
            
            // 重置输入和反馈
            answerInput.value = '';
            feedbackArea.classList.add('hidden');
            correctFeedback.classList.add('hidden');
            wrongFeedback.classList.add('hidden');
            
            // 自动聚焦输入框
            answerInput.focus();
            
            // 更新导航按钮状态
            prevBtn.disabled = currentIndex === 0;
            nextBtn.innerHTML = currentIndex === currentVocabulary.length - 1 ? 
                '完成学习' : '下一个 <i class="fa fa-arrow-right ml-2"></i>';
            
            // 如果已有答案，显示出来
            if (userAnswers[currentIndex] !== null) {
                answerInput.value = userAnswers[currentIndex].userAnswer;
                
                // 显示反馈
                feedbackArea.classList.remove('hidden');
                if (userAnswers[currentIndex].isCorrect) {
                    correctFeedback.classList.remove('hidden');
                } else {
                    wrongFeedback.classList.remove('hidden');
                    correctAnswer.textContent = currentMode === 'english-to-chinese' ? 
                        word.chinese : word.english;
                }
            }
            
            // 添加动画效果
            wordDisplay.classList.add('scale-110');
            setTimeout(() => {
                wordDisplay.classList.remove('scale-110');
            }, 300);
            
            // 更新进度
            updateProgressDisplay();
        }

        // 检查答案
        function checkAnswer() {
            const userAnswer = answerInput.value.trim();
            const word = currentVocabulary[currentIndex];
            let isCorrect = false;
            
            // 检查答案是否正确
            if (currentMode === 'english-to-chinese') {
                // 中文答案不区分大小写，去掉可能的空格
                isCorrect = userAnswer.replace(/\s/g, '') === word.chinese.replace(/\s/g, '');
            } else {
                // 英文答案不区分大小写
                isCorrect = userAnswer.toLowerCase() === word.english.toLowerCase();
            }
            
            // 保存答案
            userAnswers[currentIndex] = {
                userAnswer: userAnswer,
                isCorrect: isCorrect
            };
            
            // 显示反馈
            feedbackArea.classList.remove('hidden');
            if (isCorrect) {
                correctFeedback.classList.remove('hidden');
                wrongFeedback.classList.add('hidden');
                
                // 添加正确动画
                wordDisplay.classList.add('text-green-500');
                setTimeout(() => {
                    wordDisplay.classList.remove('text-green-500');
                }, 1000);
            } else {
                wrongFeedback.classList.remove('hidden');
                correctFeedback.classList.add('hidden');
                correctAnswer.textContent = currentMode === 'english-to-chinese' ? 
                    word.chinese : word.english;
            }
            
            // 更新进度
            updateProgressDisplay();
        }

        // 前往上一个单词
        function goToPreviousWord() {
            if (currentIndex > 0) {
                currentIndex--;
                displayCurrentWord();
            }
        }

        // 前往下一个单词
        function goToNextWord() {
            if (currentIndex < currentVocabulary.length - 1) {
                currentIndex++;
                displayCurrentWord();
            } else {
                // 完成学习，显示结果
                showCompletion();
            }
        }

        // 显示完成界面
        function showCompletion() {
            // 计算正确数量和正确率
            const correctCount = userAnswers.filter(answer => answer !== null && answer.isCorrect).length;
            const percentage = Math.round((correctCount / currentVocabulary.length) * 100);
            
            // 更新结果显示
            resultTotal.textContent = currentVocabulary.length;
            resultCorrect.textContent = correctCount;
            resultPercentage.textContent = `${percentage}%`;
            
            // 更新UI
            learningArea.classList.add('hidden');
            completionArea.classList.remove('hidden');
        }

        // 重新学习
        function restartLearning() {
            startLearning(currentMode);
        }

        // 切换模式
        function switchMode() {
            const newMode = currentMode === 'english-to-chinese' ? 'chinese-to-english' : 'english-to-chinese';
            startLearning(newMode);
        }

        // 播放发音
        function playPronunciation() {
            if (!soundEnabled) return;
            
            const word = currentVocabulary[currentIndex];
            const textToSpeak = word.english;
            
            // 使用Web Speech API
            const utterance = new SpeechSynthesisUtterance(textToSpeak);
            utterance.lang = 'en-US'; // 使用美式英语发音
            utterance.rate = 0.8; // 语速稍慢，适合学习
            window.speechSynthesis.speak(utterance);
            
            // 添加发音动画
            pronunciationBtn.classList.add('animate-pulse');
            setTimeout(() => {
                pronunciationBtn.classList.remove('animate-pulse');
            }, 1000);
        }

        // 切换声音开关
        function toggleSound() {
            soundEnabled = !soundEnabled;
            const icon = soundToggle.querySelector('i');
            
            if (soundEnabled) {
                icon.classList.remove('fa-volume-off');
                icon.classList.add('fa-volume-up');
            } else {
                icon.classList.remove('fa-volume-up');
                icon.classList.add('fa-volume-off');
                // 停止任何正在播放的语音
                window.speechSynthesis.cancel();
            }
        }

        // 更新进度显示
        function updateProgressDisplay() {
            const answeredCount = userAnswers.filter(answer => answer !== null).length;
            const percentage = Math.round((answeredCount / currentVocabulary.length) * 100);
            
            // 更新进度数字
            progressCount.textContent = answeredCount;
            mobileProgressCount.textContent = answeredCount;
            
            // 更新进度条
            progressBar.style.width = `${percentage}%`;
        }

        // 启动应用
        document.addEventListener('DOMContentLoaded', init);
    </script>
</body>
</html>

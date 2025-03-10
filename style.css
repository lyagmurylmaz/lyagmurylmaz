<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sağlıklı Yaşam</title>
    <style>
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f5f5f5;
        }
        
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        
        nav {
            background-color: #388E3C;
            padding: 10px 0;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        
        nav li {
            display: inline-block;
            margin: 0 15px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        
        .search-section {
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }
        
        .search-section input {
            width: 70%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        
        .search-section button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        
        .section {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .column {
            float: left;
            width: 31%;
            margin: 1%;
        }
        
        .clearfix::after {
            content: "";
            clear: both;
            display: table;
        }
        
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
        }
        
        @media screen and (max-width: 768px) {
            .column {
                width: 98%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Sağlıklı Yaşam</h1>
        <p>Daha iyi bir yaşam için güncel bilgiler</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#">Ana Sayfa</a></li>
            <li><a href="#">Beslenme</a></li>
            <li><a href="#">Egzersiz</a></li>
            <li><a href="#">Zihinsel Sağlık</a></li>
            <li><a href="#">Tarifler</a></li>
            <li><a href="#">Sağlık Hesaplamaları</a></li>
            <li><a href="#">Hakkımızda</a></li>
        </ul>
    </nav>
    
    <div class="container">
        <div class="search-section">
            <h2>Bilgi Ara</h2>
            <form id="searchForm">
                <input type="text" id="searchInput" placeholder="Vitamin, beslenme, egzersiz...">
                <button type="submit">Ara</button>
            </form>
            <div id="searchResults"></div>
        </div>
        
        <div class="section">
            <h2>Son Eklenen Makaleler</h2>
            <div class="clearfix">
                <div class="column">
                    <h3>Bağışıklık Sistemini Güçlendiren Besinler</h3>
                    <p>Kış aylarında bağışıklık sisteminizi desteklemek için tüketebileceğiniz en etkili besinler...</p>
                    <a href="#">Devamını Oku</a>
                </div>
                <div class="column">
                    <h3>Ev Ortamında Yapılabilecek Egzersizler</h3>
                    <p>Spor salonuna gitmeden evde kolayca yapabileceğiniz etkili egzersiz rutinleri...</p>
                    <a href="#">Devamını Oku</a>
                </div>
                <div class="column">
                    <h3>Stres Yönetimi Teknikleri</h3>
                    <p>Günlük hayatın stresini azaltmak için bilimsel olarak kanıtlanmış teknikler...</p>
                    <a href="#">Devamını Oku</a>
                </div>
            </div>
        </div>
        
        <div class="section">
            <h2>Sağlık Hesaplamaları</h2>
            <div class="clearfix">
                <div class="column">
                    <h3>Vücut Kitle İndeksi Hesaplama</h3>
                    <form id="bmiForm">
                        <p>Boy (cm): <input type="number" id="height"></p>
                        <p>Kilo (kg): <input type="number" id="weight"></p>
                        <button type="button" onclick="calculateBMI()">Hesapla</button>
                    </form>
                    <p id="bmiResult"></p>
                </div>
                <div class="column">
                    <h3>Günlük Kalori İhtiyacı</h3>
                    <form id="calorieForm">
                        <p>Yaş: <input type="number" id="age"></p>
                        <p>Cinsiyet: 
                            <select id="gender">
                                <option value="male">Erkek</option>
                                <option value="female">Kadın</option>
                            </select>
                        </p>
                        <p>Aktivite Seviyesi: 
                            <select id="activity">
                                <option value="low">Düşük</option>
                                <option value="medium">Orta</option>
                                <option value="high">Yüksek</option>
                            </select>
                        </p>
                        <button type="button" onclick="calculateCalories()">Hesapla</button>
                    </form>
                    <p id="calorieResult"></p>
                </div>
                <div class="column">
                    <h3>Su İhtiyacı Hesaplama</h3>
                    <form id="waterForm">
                        <p>Kilo (kg): <input type="number" id="waterWeight"></p>
                        <p>Aktivite Seviyesi: 
                            <select id="waterActivity">
                                <option value="low">Düşük</option>
                                <option value="medium">Orta</option>
                                <option value="high">Yüksek</option>
                            </select>
                        </p>
                        <button type="button" onclick="calculateWater()">Hesapla</button>
                    </form>
                    <p id="waterResult"></p>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <p>&copy; 2025 Sağlıklı Yaşam. Tüm hakları saklıdır.</p>
        <p>Bu sitedeki bilgiler yalnızca bilgilendirme amaçlıdır ve tıbbi tavsiye yerine geçmez.</p>
    </footer>

    <script>
        // Veritabanı bağlantısı simülasyonu
        const healthDatabase = {
            articles: [
                { 
                    id: 1, 
                    title: "Bağışıklık Sistemini Güçlendiren Besinler", 
                    content: "Bağışıklık sisteminizi güçlendirmek için...", 
                    category: "beslenme" 
                },
                { 
                    id: 2, 
                    title: "Ev Ortamında Yapılabilecek Egzersizler", 
                    content: "Evde yapabileceğiniz egzersizler...", 
                    category: "egzersiz" 
                },
                { 
                    id: 3, 
                    title: "Stres Yönetimi Teknikleri", 
                    content: "Stres yönetimi için kullanabileceğiniz...", 
                    category: "zihinsel-saglik" 
                }
            ],
            nutritionData: {
                foods: [
                    { name: "Elma", calories: 52, protein: 0.3, carbs: 14, fat: 0.2 },
                    { name: "Tavuk Göğsü", calories: 165, protein: 31, carbs: 0, fat: 3.6 },
                    { name: "Brokoli", calories: 34, protein: 2.8, carbs: 7, fat: 0.4 }
                ]
            }
        };

        // Arama fonksiyonu
        document.getElementById('searchForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const query = document.getElementById('searchInput').value.toLowerCase();
            const results = healthDatabase.articles.filter(article => 
                article.title.toLowerCase().includes(query) || 
                article.content.toLowerCase().includes(query)
            );
            
            const resultsDiv = document.getElementById('searchResults');
            resultsDiv.innerHTML = '';
            
            if (results.length === 0) {
                resultsDiv.innerHTML = '<p>Sonuç bulunamadı.</p>';
            } else {
                results.forEach(result => {
                    resultsDiv.innerHTML += `
                        <div>
                            <h3>${result.title}</h3>
                            <p>${result.content.substring(0, 100)}...</p>
                            <a href="#">Devamını Oku</a>
                            <hr>
                        </div>
                    `;
                });
            }
        });

        // VKİ hesaplama
        function calculateBMI() {
            const height = document.getElementById('height').value / 100; // cm'den m'ye çevirme
            const weight = document.getElementById('weight').value;
            
            if (!height || !weight) {
                document.getElementById('bmiResult').innerHTML = 'Lütfen boy ve kilo girin.';
                return;
            }
            
            const bmi = weight / (height * height);
            let category = '';
            
            if (bmi < 18.5) category = 'Düşük Kilolu';
            else if (bmi < 25) category = 'Normal Kilolu';
            else if (bmi < 30) category = 'Fazla Kilolu';
            else category = 'Obez';
            
            document.getElementById('bmiResult').innerHTML = `
                <strong>VKİ:</strong> ${bmi.toFixed(1)} <br>
                <strong>Kategori:</strong> ${category}
            `;
        }

        // Kalori ihtiyacı hesaplama
        function calculateCalories() {
            const age = document.getElementById('age').value;
            const gender = document.getElementById('gender').value;
            const activity = document.getElementById('activity').value;
            
            if (!age) {
                document.getElementById('calorieResult').innerHTML = 'Lütfen yaş girin.';
                return;
            }
            
            // Basit BMR hesaplaması (Mifflin-St Jeor denklemi)
            let bmr = 0;
            if (gender === 'male') {
                bmr = 10 * 70 + 6.25 * 175 - 5 * age + 5; // Örnek değerler kullanıldı (70kg, 175cm)
            } else {
                bmr = 10 * 60 + 6.25 * 165 - 5 * age - 161; // Örnek değerler kullanıldı (60kg, 165cm)
            }
            
            let activityFactor = 1.2; // Düşük aktivite
            if (activity === 'medium') activityFactor = 1.55; // Orta aktivite
            else if (activity === 'high') activityFactor = 1.9; // Yüksek aktivite
            
            const calories = Math.round(bmr * activityFactor);
            
            document.getElementById('calorieResult').innerHTML = `
                <strong>Günlük Kalori İhtiyacı:</strong> ${calories} kalori
            `;
        }

        // Su ihtiyacı hesaplama
        function calculateWater() {
            const weight = document.getElementById('waterWeight').value;
            const activity = document.getElementById('waterActivity').value;
            
            if (!weight) {
                document.getElementById('waterResult').innerHTML = 'Lütfen kilo girin.';
                return;
            }
            
            let waterPerKg = 30; // mL/kg
            if (activity === 'medium') waterPerKg = 35;
            else if (activity === 'high') waterPerKg = 40;
            
            const waterInML = weight * waterPerKg;
            const waterInL = (waterInML / 1000).toFixed(1);
            
            document.getElementById('waterResult').innerHTML = `
                <strong>Günlük Su İhtiyacı:</strong> ${waterInL} litre
            `;
        }
    </script>
</body>
</html>

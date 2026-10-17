<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>By EMorrison — Профиль</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0b0f17;
            color: #e1e7ed;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .profile-card {
            width: 100%;
            max-width: 750px;
            background: #121824;
            border-radius: 16px;
            overflow: hidden;
            border: 1px solid #1e293b;
            box-shadow: 0 12px 32px rgba(0, 0, 0, 0.6);
        }

        /* Баннер */
        .banner {
            position: relative;
            height: 180px;
            background: linear-gradient(135deg, #0f172a 0%, #1e1b4b 100%), 
                        radial-gradient(circle at top right, rgba(0, 168, 255, 0.2), transparent 50%);
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            border-bottom: 2px solid #1e293b;
            padding: 20px;
        }

        .banner h1 {
            font-size: 36px;
            font-weight: 800;
            letter-spacing: 2px;
            color: #ffffff;
            text-transform: uppercase;
            text-shadow: 0 0 20px rgba(0, 168, 255, 0.5);
        }

        .banner span {
            display: block;
            font-size: 14px;
            color: #00a8ff;
            margin-top: 5px;
            letter-spacing: 1px;
        }

        /* Нижняя часть с кнопками и информацией */
        .content {
            padding: 25px;
        }

        .top-row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
            margin-bottom: 25px;
            border-bottom: 1px solid #1e293b;
            padding-bottom: 20px;
        }

        .user-title {
            font-size: 16px;
            font-weight: 600;
            color: #94a3b8;
        }

        .buttons {
            display: flex;
            gap: 10px;
        }

        .btn {
            background: #0077ff;
            color: white;
            padding: 8px 20px;
            border-radius: 20px;
            text-decoration: none;
            font-weight: 700;
            font-size: 14px;
            box-shadow: 0 0 15px rgba(0, 119, 255, 0.4);
            transition: 0.2s ease;
        }

        .btn:hover {
            background: #0088ff;
            box-shadow: 0 0 20px rgba(0, 136, 255, 0.7);
            transform: translateY(-2px);
        }

        .btn.secondary {
            background: #1e293b;
            color: #00a8ff;
            border: 1px solid #00a8ff;
            box-shadow: none;
        }

        .btn.secondary:hover {
            background: #00a8ff;
            color: white;
        }

        /* Секции истории */
        .section-title {
            font-size: 18px;
            color: #00a8ff;
            margin: 25px 0 15px 0;
            display: flex;
            align-items: center;
            gap: 8px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .history-item {
            background: #1a2332;
            border-left: 4px solid #00a8ff;
            padding: 12px 16px;
            margin-bottom: 10px;
            border-radius: 6px;
            transition: 0.2s;
        }

        .history-item.current {
            border-left-color: #e74c3c;
        }

        .history-item:hover {
            background: #202c40;
        }

        .history-header {
            font-weight: bold;
            font-size: 15px;
            margin-bottom: 4px;
            color: #f8fafc;
        }

        .history-details {
            font-size: 13px;
            color: #94a3b8;
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }

        .respect {
            color: #2ecc71;
            font-weight: bold;
        }

        .current-badge {
            color: #e74c3c;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="profile-card">
        <!-- Шапка (Баннер) -->
        <div class="banner">
            <div>
                <h1>E. Morrison</h1>
                <span>BIOGRAPHY & HISTORY</span>
            </div>
        </div>

        <!-- Основной контент -->
        <div class="content">
            <div class="top-row">
                <div class="user-title">
                    История фракций
                </div>
                <div class="buttons">
                    <a href="https://vk.com" target="_blank" class="btn">VK</a>
                    <a href="https://t.me" target="_blank" class="btn">TG</a>
                    <a href="#" class="btn secondary">Biography</a>
                </div>
            </div>

            <!-- История ЧО -->
            <div class="section-title">?? История ЧО</div>

            <div class="history-item">
                <div class="history-header">Пассажирский автотранспорт</div>
                <div class="history-details">
                    <span>?? 24.06.2024 — 03.01.2026</span>
                    <span>?? Вице-президент холдинга</span>
                    <span>?? Anton Synkov — <span class="respect">Respect</span></span>
                </div>
            </div>

            <div class="history-item">
                <div class="history-header">АО «Арвутранспортэйшн»</div>
                <div class="history-details">
                    <span>?? 10.01.2026 — 01.05.2026</span>
                    <span>?? Главный инженер</span>
                    <span>?? Arvo Elnomdusuari — <span class="respect">Respect</span></span>
                </div>
            </div>

            <div class="history-item">
                <div class="history-header">Пассажирский автотранспорт</div>
                <div class="history-details">
                    <span>?? 01.05.2026 — 08.06.2026</span>
                    <span>?? Финансовый директор</span>
                    <span>?? Anton Synkov — <span class="respect">Respect</span></span>
                </div>
            </div>

            <div class="history-item current">
                <div class="history-header">АО «Приволжск Авто Газ»</div>
                <div class="history-details">
                    <span>?? 08.06.2026 — <span class="current-badge">Н. В.</span></span>
                    <span>?? <span class="current-badge">Ген. директор</span></span>
                </div>
            </div>

            <!-- История гос. структур -->
            <div class="section-title">??? История гос. структур</div>

            <div class="history-item">
                <div class="history-header">ЦГБ г. Приволжск</div>
                <div class="history-details">
                    <span>?? 23.05.2026 — 03.06.2026</span>
                    <span>?? Фельдшер</span>
                    <span>?? Alexander Vavilov — <span class="respect">Respect</span></span>
                </div>
            </div>

            <div class="history-item current">
                <div class="history-header">ГУ МВД г. Невский</div>
                <div class="history-details">
                    <span>?? 29.09.2026 — <span class="current-badge">Н. В.</span></span>
                    <span>?? <span class="current-badge">Сотрудник</span></span>
                    <span>?? Alisa_Desize</span>
                </div>
            </div>
        </div>
    </div>

</body>
</html>

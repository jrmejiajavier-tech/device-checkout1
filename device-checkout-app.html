<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <meta name="apple-mobile-web-app-title" content="Device Checkout">
    <title>Device Checkout System</title>
    
    <!-- App Icon for iPad -->
    <link rel="apple-touch-icon" sizes="180x180" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 180 180'><defs><linearGradient id='grad' x1='0%25' y1='0%25' x2='100%25' y2='100%25'><stop offset='0%25' style='stop-color:%23667eea'/><stop offset='100%25' style='stop-color:%23764ba2'/></linearGradient></defs><rect width='180' height='180' fill='url(%23grad)'/><text x='90' y='110' font-size='80' text-anchor='middle' fill='white'>📱</text></svg>">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 15px;
            display: flex;
            gap: 15px;
            overflow-x: hidden;
        }

        .main-container {
            flex: 1;
            max-width: 100%;
            min-width: 0;
        }

        .sidebar {
            width: 320px;
            min-width: 280px;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            overflow: hidden;
            max-height: calc(100vh - 30px);
            display: flex;
            flex-direction: column;
        }

        .sidebar-header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px;
            text-align: center;
        }

        .sidebar-header h3 {
            font-size: 18px;
            margin-bottom: 5px;
        }

        .sidebar-content {
            padding: 15px;
            overflow-y: auto;
            flex: 1;
            -webkit-overflow-scrolling: touch;
        }

        .sidebar-device {
            background: #f9fafb;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 10px;
            border-left: 4px solid #667eea;
            touch-action: manipulation;
        }

        .sidebar-device-number {
            font-weight: 700;
            color: #667eea;
            font-size: 18px;
            margin-bottom: 5px;
        }

        .sidebar-device-name {
            color: #333;
            font-size: 16px;
        }

        .sidebar-empty {
            text-align: center;
            padding: 40px 20px;
            color: #999;
        }

        .sidebar-count {
            font-size: 14px;
            opacity: 0.9;
        }

        /* iPad Portrait and smaller screens */
        @media (max-width: 1024px) {
            body {
                flex-direction: column;
                padding: 10px;
                gap: 10px;
            }

            .sidebar {
                width: 100%;
                max-height: 300px;
                order: -1;
                min-width: auto;
            }

            .main-container {
                max-width: 100%;
            }
        }

        /* Mobile phones */
        @media (max-width: 768px) {
            .sidebar {
                max-height: 250px;
            }

            .tabs {
                overflow-x: auto;
                -webkit-overflow-scrolling: touch;
            }

            .tab {
                min-width: 120px;
                font-size: 14px;
                padding: 15px 10px;
            }
        }

        .container {
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 25px 20px;
            text-align: center;
        }

        .header h1 {
            font-size: 20px;
            margin-bottom: 5px;
        }

        .header h2 {
            font-size: 26px;
            margin-bottom: 10px;
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 18px;
            }

            .header h2 {
                font-size: 22px;
            }
        }

        .header h1 {
            font-size: 28px;
            margin-bottom: 10px;
        }

        .tabs {
            display: flex;
            background: #f5f5f5;
        }

        .tab {
            flex: 1;
            padding: 18px 10px;
            text-align: center;
            cursor: pointer;
            border: none;
            background: #f5f5f5;
            font-size: 15px;
            font-weight: 600;
            transition: all 0.3s;
            white-space: nowrap;
            touch-action: manipulation;
            -webkit-tap-highlight-color: transparent;
        }

        .tab:hover {
            background: #e0e0e0;
        }

        .tab.active {
            background: white;
            color: #667eea;
        }

        .content {
            padding: 25px 20px;
            overflow-y: auto;
            -webkit-overflow-scrolling: touch;
        }

        @media (max-width: 768px) {
            .content {
                padding: 20px 15px;
            }
        }

        .tab-content {
            display: none;
        }

        .tab-content.active {
            display: block;
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #333;
        }

        input[type="text"],
        input[type="tel"] {
            width: 100%;
            padding: 14px;
            border: 2px solid #e0e0e0;
            border-radius: 8px;
            font-size: 17px;
            transition: border-color 0.3s;
            -webkit-appearance: none;
            appearance: none;
        }

        input[type="text"]:focus,
        input[type="tel"]:focus {
            outline: none;
            border-color: #667eea;
        }

        .btn {
            width: 100%;
            padding: 16px;
            border: none;
            border-radius: 8px;
            font-size: 17px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            touch-action: manipulation;
            -webkit-tap-highlight-color: transparent;
        }

        .btn-primary {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }

        .btn-primary:active {
            transform: translateY(0);
        }

        .btn-success {
            background: #10b981;
            color: white;
        }

        .btn-success:hover {
            background: #059669;
            transform: translateY(-2px);
        }

        .btn-success:active {
            transform: translateY(0);
        }

        .device-list {
            margin-top: 30px;
            max-height: 500px;
            overflow-y: auto;
            -webkit-overflow-scrolling: touch;
        }

        .device-item {
            background: #f9fafb;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 10px;
            border-left: 4px solid #667eea;
            touch-action: manipulation;
        }

        .device-item.returned {
            border-left-color: #10b981;
            opacity: 0.7;
        }

        .device-info {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 10px;
        }

        .device-details {
            flex: 1;
        }

        .device-details strong {
            color: #667eea;
        }

        .device-details p {
            margin: 5px 0;
            color: #666;
        }

        .status-badge {
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 600;
        }

        .status-checked-out {
            background: #fef3c7;
            color: #92400e;
        }

        .status-returned {
            background: #d1fae5;
            color: #065f46;
        }

        .checkbox-group {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 15px;
            background: #fef3c7;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .checkbox-group input[type="checkbox"] {
            width: 24px;
            height: 24px;
            cursor: pointer;
            touch-action: manipulation;
        }

        .checkbox-group label {
            margin: 0;
            cursor: pointer;
        }

        .message {
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
            display: none;
        }

        .message.success {
            background: #d1fae5;
            color: #065f46;
            display: block;
        }

        .message.error {
            background: #fee2e2;
            color: #991b1b;
            display: block;
        }

        .empty-state {
            text-align: center;
            padding: 40px;
            color: #999;
        }

        .password-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 1000;
        }

        .password-modal.show {
            display: flex;
        }

        .password-box {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.3);
            max-width: 400px;
            width: 90%;
        }

        .password-box h3 {
            margin-bottom: 20px;
            color: #667eea;
        }

        .password-box input {
            width: 100%;
            padding: 14px;
            border: 2px solid #e0e0e0;
            border-radius: 8px;
            font-size: 18px;
            margin-bottom: 15px;
            -webkit-appearance: none;
            appearance: none;
        }

        .password-buttons {
            display: flex;
            gap: 10px;
        }

        .password-buttons button {
            flex: 1;
        }

        .btn-cancel {
            background: #6b7280;
            color: white;
        }

        .btn-cancel:hover {
            background: #4b5563;
        }

        .btn-danger {
            background: #dc2626;
            color: white;
        }

        .btn-danger:hover {
            background: #b91c1c;
        }

        .btn-danger:active {
            transform: translateY(0);
        }

        .history-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .history-column {
            background: #f9fafb;
            border-radius: 12px;
            padding: 15px;
            border: 2px solid #e5e7eb;
        }

        .history-date-header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 12px;
            border-radius: 8px;
            margin-bottom: 15px;
            text-align: center;
            font-weight: 600;
            font-size: 16px;
        }

        .history-device-item {
            background: white;
            padding: 12px;
            border-radius: 8px;
            margin-bottom: 10px;
            border-left: 4px solid #667eea;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
        }

        .history-device-item.returned {
            border-left-color: #10b981;
        }

        @media (max-width: 768px) {
            .history-grid {
                grid-template-columns: 1fr;
            }
        }

        .confirm-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 1000;
        }

        .confirm-modal.show {
            display: flex;
        }

        .confirm-box {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.3);
            max-width: 400px;
            width: 90%;
            text-align: center;
        }

        .confirm-box h3 {
            margin-bottom: 15px;
            color: #dc2626;
        }

        .confirm-box p {
            margin-bottom: 20px;
            color: #666;
        }

        .confirm-buttons {
            display: flex;
            gap: 10px;
        }

        .confirm-buttons button {
            flex: 1;
        }

        .autocomplete-suggestions {
            position: absolute;
            background: white;
            border: 2px solid #667eea;
            border-radius: 8px;
            max-height: 200px;
            overflow-y: auto;
            z-index: 100;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            display: none;
        }

        .autocomplete-suggestions.show {
            display: block;
        }

        .suggestion-item {
            padding: 14px;
            cursor: pointer;
            border-bottom: 1px solid #f0f0f0;
            touch-action: manipulation;
            -webkit-tap-highlight-color: transparent;
        }

        .suggestion-item:hover {
            background: #f3f4f6;
        }

        .suggestion-item:last-child {
            border-bottom: none;
        }

        .suggestion-name {
            font-weight: 600;
            color: #333;
        }

        .suggestion-phone {
            font-size: 14px;
            color: #666;
            margin-top: 3px;
        }

        .form-group {
            position: relative;
        }
    </style>
</head>
<body>
    <div class="main-container">
        <div class="container">
        <div class="header">
            <h1 style="font-size: 24px; margin-bottom: 5px;">Grace Bible Church</h1>
            <h2 style="font-size: 32px; margin-bottom: 10px;">📱 Sistema de Préstamo de Dispositivos</h2>
            <p id="current-date"></p>
        </div>

        <div class="tabs">
            <button class="tab active" onclick="switchTab('checkout')">Pedir Dispositivo</button>
            <button class="tab" onclick="switchTab('return')">Devolver Dispositivo</button>
            <button class="tab" onclick="switchTab('view')">Ver Todos</button>
            <button class="tab" id="history-tab" style="display: none;" onclick="switchTab('history')">Historial</button>
            <button class="tab" id="unlock-tab" onclick="unlockHistory()">🔒</button>
        </div>

        <div class="content">
            <!-- Check Out Tab -->
            <div id="checkout" class="tab-content active">
                <h2 style="margin-bottom: 20px;">Pedir un Dispositivo</h2>
                <div id="checkout-message" class="message"></div>
                
                <form id="checkout-form" onsubmit="checkoutDevice(event)">
                    <div class="form-group">
                        <label for="checkout-name">Nombre Completo *</label>
                        <input type="text" id="checkout-name" required placeholder="Ingrese su nombre completo" autocomplete="off" oninput="showNameSuggestions(this.value)">
                        <div id="name-suggestions" class="autocomplete-suggestions"></div>
                    </div>

                    <div class="form-group">
                        <label for="checkout-phone">Número de Teléfono *</label>
                        <input type="tel" id="checkout-phone" required placeholder="(555) 123-4567">
                    </div>

                    <div class="form-group">
                        <label for="checkout-device">Número de Dispositivo *</label>
                        <input type="text" id="checkout-device" required placeholder="ej., DEV-001">
                    </div>

                    <button type="submit" class="btn btn-primary">Pedir Dispositivo</button>
                </form>
            </div>

            <!-- Return Tab -->
            <div id="return" class="tab-content">
                <h2 style="margin-bottom: 20px;">Devolver un Dispositivo</h2>
                <div id="return-message" class="message"></div>
                
                <form id="return-form" onsubmit="returnDevice(event)">
                    <div class="form-group">
                        <label for="return-identifier">Nombre o Número de Teléfono *</label>
                        <input type="text" id="return-identifier" required placeholder="Ingrese su nombre o número de teléfono">
                    </div>

                    <div class="checkbox-group">
                        <input type="checkbox" id="confirm-return" required>
                        <label for="confirm-return">Confirmo que estoy devolviendo el dispositivo</label>
                    </div>

                    <button type="submit" class="btn btn-success">Devolver Dispositivo</button>
                </form>

                <div id="matching-devices" class="device-list"></div>
            </div>

            <!-- View All Tab -->
            <div id="view" class="tab-content">
                <h2 style="margin-bottom: 20px;">Dispositivos de Hoy</h2>
                <div id="all-devices" class="device-list"></div>
            </div>

            <!-- History Tab -->
            <div id="history" class="tab-content">
                <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; flex-wrap: wrap; gap: 10px;">
                    <h2 style="margin: 0;">Historial de Días Anteriores</h2>
                    <button class="btn btn-danger" style="width: auto; padding: 12px 24px;" onclick="confirmDeleteHistory()">
                        🗑️ Borrar Historial
                    </button>
                </div>
                <div id="history-devices" class="history-grid"></div>
            </div>
        </div>
    </div>
    </div>

    <!-- Sidebar with active devices -->
    <div class="sidebar">
        <div class="sidebar-header">
            <h3>📱 Dispositivos Activos</h3>
            <p class="sidebar-count" id="active-count">0 dispositivos prestados</p>
        </div>
        <div class="sidebar-content" id="sidebar-devices">
            <div class="sidebar-empty">
                <p>No hay dispositivos prestados</p>
            </div>
        </div>
    </div>

    <!-- Password Modal -->
    <div id="password-modal" class="password-modal">
        <div class="password-box">
            <h3>🔒 Acceso al Historial</h3>
            <p style="margin-bottom: 15px; color: #666;">Ingrese la contraseña para ver el historial:</p>
            <input type="password" id="password-input" placeholder="Contraseña" onkeypress="if(event.key==='Enter') checkPassword()">
            <div class="password-buttons">
                <button class="btn btn-cancel" onclick="closePasswordModal()">Cancelar</button>
                <button class="btn btn-primary" onclick="checkPassword()">Entrar</button>
            </div>
            <p id="password-error" style="color: #dc2626; margin-top: 10px; display: none;">Contraseña incorrecta</p>
        </div>
    </div>

    <!-- Confirm Delete Modal -->
    <div id="confirm-modal" class="confirm-modal">
        <div class="confirm-box">
            <h3>⚠️ Confirmar Eliminación</h3>
            <p>¿Está seguro que desea borrar todo el historial? Esta acción no se puede deshacer.</p>
            <div class="confirm-buttons">
                <button class="btn btn-cancel" onclick="closeConfirmModal()">Cancelar</button>
                <button class="btn btn-danger" onclick="deleteHistory()">Borrar Todo</button>
            </div>
        </div>
    </div>

    <script>
        // Initialize and show current date
        function updateCurrentDate() {
            const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
            const today = new Date().toLocaleDateString('es-ES', options);
            document.getElementById('current-date').textContent = today;
        }

        // Get today's date as string (YYYY-MM-DD)
        function getTodayString() {
            const today = new Date();
            return today.toISOString().split('T')[0];
        }

        // Initialize localStorage
        function getDevices() {
            const devices = localStorage.getItem('devices');
            return devices ? JSON.parse(devices) : [];
        }

        function saveDevices(devices) {
            localStorage.setItem('devices', JSON.stringify(devices));
        }

        // Get and save registered users
        function getRegisteredUsers() {
            const users = localStorage.getItem('registeredUsers');
            return users ? JSON.parse(users) : [];
        }

        function saveRegisteredUser(name, phone) {
            const users = getRegisteredUsers();
            // Check if user already exists
            const existingUser = users.find(u => 
                u.name.toLowerCase() === name.toLowerCase() || u.phone === phone
            );
            
            if (!existingUser) {
                users.push({ name, phone });
                localStorage.setItem('registeredUsers', JSON.stringify(users));
            } else if (existingUser.name.toLowerCase() !== name.toLowerCase() || existingUser.phone !== phone) {
                // Update existing user info
                existingUser.name = name;
                existingUser.phone = phone;
                localStorage.setItem('registeredUsers', JSON.stringify(users));
            }
        }

        // Show name suggestions
        function showNameSuggestions(input) {
            const suggestionsDiv = document.getElementById('name-suggestions');
            
            if (input.length < 2) {
                suggestionsDiv.classList.remove('show');
                return;
            }

            const users = getRegisteredUsers();
            const matches = users.filter(u => 
                u.name.toLowerCase().includes(input.toLowerCase())
            );

            if (matches.length === 0) {
                suggestionsDiv.classList.remove('show');
                return;
            }

            suggestionsDiv.innerHTML = '';
            matches.forEach(user => {
                const div = document.createElement('div');
                div.className = 'suggestion-item';
                div.innerHTML = `
                    <div class="suggestion-name">${user.name}</div>
                    <div class="suggestion-phone">${user.phone}</div>
                `;
                div.onclick = () => selectUser(user);
                suggestionsDiv.appendChild(div);
            });

            suggestionsDiv.classList.add('show');
        }

        // Select user from suggestions
        function selectUser(user) {
            document.getElementById('checkout-name').value = user.name;
            document.getElementById('checkout-phone').value = user.phone;
            document.getElementById('name-suggestions').classList.remove('show');
        }

        // Hide suggestions when clicking outside
        document.addEventListener('click', function(e) {
            if (!e.target.closest('.form-group')) {
                document.getElementById('name-suggestions').classList.remove('show');
            }
        });

        // Get devices for today only
        function getTodayDevices() {
            const allDevices = getDevices();
            const today = getTodayString();
            return allDevices.filter(d => d.date === today);
        }

        // Get devices from previous days
        function getHistoryDevices() {
            const allDevices = getDevices();
            const today = getTodayString();
            return allDevices.filter(d => d.date !== today);
        }

        // Switch tabs
        function switchTab(tabName) {
            document.querySelectorAll('.tab').forEach(tab => tab.classList.remove('active'));
            document.querySelectorAll('.tab-content').forEach(content => content.classList.remove('active'));
            
            event.target.classList.add('active');
            document.getElementById(tabName).classList.add('active');

            // Lock history when leaving history tab
            if (historyUnlocked && tabName !== 'history') {
                historyUnlocked = false;
                document.getElementById('history-tab').style.display = 'none';
                document.getElementById('unlock-tab').style.display = 'block';
            }

            if (tabName === 'view') {
                displayAllDevices();
            } else if (tabName === 'history') {
                displayHistoryDevices();
            } else if (tabName === 'return') {
                document.getElementById('matching-devices').innerHTML = '';
            }

            updateSidebar();
        }

        // Check out device
        function checkoutDevice(event) {
            event.preventDefault();
            
            const name = document.getElementById('checkout-name').value.trim();
            const phone = document.getElementById('checkout-phone').value.trim();
            const deviceNumber = document.getElementById('checkout-device').value.trim();

            // Check if device is already checked out today and not returned
            const todayDevices = getTodayDevices();
            const existingDevice = todayDevices.find(d => 
                d.deviceNumber.toLowerCase() === deviceNumber.toLowerCase() && !d.returned
            );

            if (existingDevice) {
                showMessage('checkout-message', 'error', `El dispositivo ${deviceNumber} ya está prestado. Debe ser devuelto primero.`);
                setTimeout(() => {
                    hideMessage('checkout-message');
                }, 4000);
                return;
            }

            const devices = getDevices();
            
            const device = {
                id: Date.now(),
                name: name,
                phone: phone,
                deviceNumber: deviceNumber,
                date: getTodayString(),
                checkedOutAt: new Date().toISOString(),
                returned: false
            };

            devices.push(device);
            saveDevices(devices);

            // Save user info for future autocomplete
            saveRegisteredUser(name, phone);

            showMessage('checkout-message', 'success', `¡Dispositivo ${deviceNumber} prestado exitosamente a ${name}!`);
            document.getElementById('checkout-form').reset();

            setTimeout(() => {
                hideMessage('checkout-message');
            }, 3000);

            updateSidebar();
        }

        // Return device
        function returnDevice(event) {
            event.preventDefault();
            
            const identifier = document.getElementById('return-identifier').value.trim().toLowerCase();
            const devices = getDevices();
            const todayDevices = getTodayDevices();

            const matchingDevices = todayDevices.filter(d => 
                !d.returned && 
                (d.name.toLowerCase().includes(identifier) || d.phone.includes(identifier))
            );

            if (matchingDevices.length === 0) {
                showMessage('return-message', 'error', 'No se encontraron dispositivos prestados hoy para este nombre o número de teléfono.');
                return;
            }

            if (matchingDevices.length === 1) {
                const device = matchingDevices[0];
                const allDevices = getDevices();
                const deviceIndex = allDevices.findIndex(d => d.id === device.id);
                allDevices[deviceIndex].returned = true;
                allDevices[deviceIndex].returnedAt = new Date().toISOString();
                saveDevices(allDevices);
                
                showMessage('return-message', 'success', `¡Dispositivo ${device.deviceNumber} devuelto exitosamente!`);
                document.getElementById('return-form').reset();
                document.getElementById('matching-devices').innerHTML = '';
                updateSidebar();
            } else {
                displayMatchingDevices(matchingDevices);
            }
        }

        // Display matching devices for return
        function displayMatchingDevices(devices) {
            const container = document.getElementById('matching-devices');
            container.innerHTML = '<h3 style="margin: 20px 0;">Seleccione el dispositivo a devolver:</h3>';

            devices.forEach(device => {
                const div = document.createElement('div');
                div.className = 'device-item';
                div.innerHTML = `
                    <div class="device-info">
                        <div class="device-details">
                            <strong>Dispositivo: ${device.deviceNumber}</strong>
                            <p>Nombre: ${device.name}</p>
                            <p>Teléfono: ${device.phone}</p>
                            <p>Prestado: ${new Date(device.checkedOutAt).toLocaleString('es-ES')}</p>
                        </div>
                        <button class="btn btn-success" style="width: auto; padding: 10px 20px;" onclick="confirmReturn(${device.id})">
                            Devolver Este Dispositivo
                        </button>
                    </div>
                `;
                container.appendChild(div);
            });
        }

        // Confirm return
        function confirmReturn(deviceId) {
            const devices = getDevices();
            const deviceIndex = devices.findIndex(d => d.id === deviceId);
            
            if (deviceIndex !== -1) {
                devices[deviceIndex].returned = true;
                devices[deviceIndex].returnedAt = new Date().toISOString();
                saveDevices(devices);
                
                showMessage('return-message', 'success', `¡Dispositivo ${devices[deviceIndex].deviceNumber} devuelto exitosamente!`);
                document.getElementById('return-form').reset();
                document.getElementById('matching-devices').innerHTML = '';
                updateSidebar();
            }
        }

        // Display all devices for today
        function displayAllDevices() {
            const container = document.getElementById('all-devices');
            const devices = getTodayDevices();

            if (devices.length === 0) {
                container.innerHTML = '<div class="empty-state"><h3>No hay dispositivos prestados hoy</h3><p>Comience pidiendo un dispositivo</p></div>';
                return;
            }

            container.innerHTML = '';
            devices.reverse().forEach(device => {
                const div = document.createElement('div');
                div.className = `device-item ${device.returned ? 'returned' : ''}`;
                div.innerHTML = `
                    <div class="device-info">
                        <div class="device-details">
                            <strong>Dispositivo: ${device.deviceNumber}</strong>
                            <p>Nombre: ${device.name}</p>
                            <p>Teléfono: ${device.phone}</p>
                            <p>Prestado: ${new Date(device.checkedOutAt).toLocaleString('es-ES')}</p>
                            ${device.returned ? `<p>Devuelto: ${new Date(device.returnedAt).toLocaleString('es-ES')}</p>` : ''}
                        </div>
                        <span class="status-badge ${device.returned ? 'status-returned' : 'status-checked-out'}">
                            ${device.returned ? '✓ Devuelto' : '⏱ Prestado'}
                        </span>
                    </div>
                `;
                container.appendChild(div);
            });
        }

        // Display history devices grouped by date in columns
        function displayHistoryDevices() {
            const container = document.getElementById('history-devices');
            const devices = getHistoryDevices();

            if (devices.length === 0) {
                container.innerHTML = '<div class="empty-state"><h3>No hay historial de días anteriores</h3><p>Los dispositivos de días pasados aparecerán aquí</p></div>';
                return;
            }

            // Group devices by date
            const devicesByDate = {};
            devices.forEach(device => {
                if (!devicesByDate[device.date]) {
                    devicesByDate[device.date] = [];
                }
                devicesByDate[device.date].push(device);
            });

            // Sort dates in descending order
            const sortedDates = Object.keys(devicesByDate).sort().reverse();

            container.innerHTML = '';
            
            sortedDates.forEach(date => {
                const dateObj = new Date(date + 'T00:00:00');
                const column = document.createElement('div');
                column.className = 'history-column';
                
                const dateHeader = document.createElement('div');
                dateHeader.className = 'history-date-header';
                dateHeader.textContent = dateObj.toLocaleDateString('es-ES', { 
                    weekday: 'long', 
                    year: 'numeric', 
                    month: 'long', 
                    day: 'numeric' 
                });
                column.appendChild(dateHeader);

                devicesByDate[date].forEach(device => {
                    const div = document.createElement('div');
                    div.className = `history-device-item ${device.returned ? 'returned' : ''}`;
                    div.innerHTML = `
                        <div style="margin-bottom: 8px;">
                            <strong style="color: #667eea; font-size: 16px;">📱 ${device.deviceNumber}</strong>
                        </div>
                        <div style="color: #333; margin-bottom: 4px;">
                            <strong>Nombre:</strong> ${device.name}
                        </div>
                        <div style="color: #666; font-size: 14px; margin-bottom: 4px;">
                            <strong>Teléfono:</strong> ${device.phone}
                        </div>
                        <div style="color: #666; font-size: 14px; margin-bottom: 4px;">
                            <strong>Prestado:</strong> ${new Date(device.checkedOutAt).toLocaleTimeString('es-ES', { hour: '2-digit', minute: '2-digit' })}
                        </div>
                        ${device.returned ? `
                            <div style="color: #10b981; font-size: 14px;">
                                <strong>✓ Devuelto:</strong> ${new Date(device.returnedAt).toLocaleTimeString('es-ES', { hour: '2-digit', minute: '2-digit' })}
                            </div>
                        ` : `
                            <div style="color: #f59e0b; font-size: 14px;">
                                <strong>⏱ No devuelto</strong>
                            </div>
                        `}
                    `;
                    column.appendChild(div);
                });

                container.appendChild(column);
            });
        }

        // Update sidebar with active devices
        function updateSidebar() {
            const todayDevices = getTodayDevices();
            const activeDevices = todayDevices.filter(d => !d.returned);
            
            const sidebarContent = document.getElementById('sidebar-devices');
            const countElement = document.getElementById('active-count');
            
            countElement.textContent = `${activeDevices.length} dispositivo${activeDevices.length !== 1 ? 's' : ''} prestado${activeDevices.length !== 1 ? 's' : ''}`;
            
            if (activeDevices.length === 0) {
                sidebarContent.innerHTML = '<div class="sidebar-empty"><p>No hay dispositivos prestados</p></div>';
                return;
            }
            
            sidebarContent.innerHTML = '';
            activeDevices.forEach(device => {
                const div = document.createElement('div');
                div.className = 'sidebar-device';
                div.innerHTML = `
                    <div class="sidebar-device-number">📱 ${device.deviceNumber}</div>
                    <div class="sidebar-device-name">${device.name}</div>
                `;
                sidebarContent.appendChild(div);
            });
        }

        // Message helpers
        function showMessage(elementId, type, text) {
            const element = document.getElementById(elementId);
            element.className = `message ${type}`;
            element.textContent = text;
        }

        function hideMessage(elementId) {
            const element = document.getElementById(elementId);
            element.style.display = 'none';
        }

        // Initialize on page load
        updateCurrentDate();
        updateSidebar();

        // Password protection for history
        let historyUnlocked = false;

        function unlockHistory() {
            if (historyUnlocked) {
                switchTab('history');
                return;
            }
            document.getElementById('password-modal').classList.add('show');
            document.getElementById('password-input').value = '';
            document.getElementById('password-error').style.display = 'none';
            setTimeout(() => {
                document.getElementById('password-input').focus();
            }, 100);
        }

        function closePasswordModal() {
            document.getElementById('password-modal').classList.remove('show');
        }

        function checkPassword() {
            const password = document.getElementById('password-input').value;
            if (password === '1234') {
                historyUnlocked = true;
                document.getElementById('password-modal').classList.remove('show');
                document.getElementById('history-tab').style.display = 'block';
                document.getElementById('unlock-tab').style.display = 'none';
                switchTab('history');
            } else {
                document.getElementById('password-error').style.display = 'block';
                document.getElementById('password-input').value = '';
                document.getElementById('password-input').focus();
            }
        }

        // Close modal when clicking outside
        document.getElementById('password-modal').addEventListener('click', function(e) {
            if (e.target === this) {
                closePasswordModal();
            }
        });

        // Confirm delete history
        function confirmDeleteHistory() {
            document.getElementById('confirm-modal').classList.add('show');
        }

        function closeConfirmModal() {
            document.getElementById('confirm-modal').classList.remove('show');
        }

        function deleteHistory() {
            const allDevices = getDevices();
            const today = getTodayString();
            
            // Keep only today's devices
            const todayDevices = allDevices.filter(d => d.date === today);
            saveDevices(todayDevices);
            
            closeConfirmModal();
            displayHistoryDevices();
            
            // Show success message
            alert('✓ Historial borrado exitosamente');
        }

        // Close confirm modal when clicking outside
        document.getElementById('confirm-modal').addEventListener('click', function(e) {
            if (e.target === this) {
                closeConfirmModal();
            }
        });
    </script>
</body>
</html>

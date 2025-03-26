<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>App de Números Móvil</title>
    <style>
        * {
            box-sizing: border-box;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        .container {
            max-width: 100%;
            padding: 10px;
        }
        h1 {
            text-align: center;
            font-size: 1.5rem;
            margin: 10px 0;
            color: #2c3e50;
        }
        .panel {
            background-color: white;
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .controls {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: 10px;
        }
        .control-group {
            display: flex;
            flex: 1;
            min-width: 120px;
        }
        button {
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            background-color: #3498db;
            color: white;
            font-weight: bold;
            cursor: pointer;
            flex: 1;
            font-size: 0.9rem;
            transition: background-color 0.2s;
        }
        button:hover {
            background-color: #2980b9;
        }
        button.secondary {
            background-color: #2ecc71;
        }
        button.secondary:hover {
            background-color: #27ae60;
        }
        button.danger {
            background-color: #e74c3c;
        }
        button.danger:hover {
            background-color: #c0392b;
        }
        .search-box {
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            width: 100%;
            font-size: 1rem;
        }
        .number-grid {
            display: grid;
            grid-template-columns: repeat(5, 1fr);
            gap: 8px;
            margin-bottom: 15px;
        }
        .number-card {
            background-color: white;
            border: 2px solid #ddd;
            border-radius: 8px;
            padding: 8px;
            text-align: center;
            cursor: pointer;
            transition: all 0.2s;
            font-weight: bold;
            aspect-ratio: 1/1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        .number-card.selected {
            background-color: #2ecc71;
            color: white;
            border-color: #27ae60;
        }
        .number-card.marked {
            background-color: #3498db;
            color: white;
            border-color: #2980b9;
        }
        .number-card .number {
            font-size: 1.2rem;
        }
        .number-card .number-name {
            font-size: 0.7rem;
            margin-top: 3px;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
            max-width: 90%;
        }
        .selected-list, .marked-list {
            margin-top: 10px;
        }
        .selected-item, .marked-item {
            background-color: #ecf0f1;
            padding: 8px 12px;
            border-radius: 5px;
            margin-bottom: 5px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .marked-item {
            background-color: #eaf2f8;
        }
        .item-actions {
            display: flex;
            gap: 5px;
        }
        .action-btn {
            padding: 5px 8px;
            font-size: 0.8rem;
            min-width: 0;
        }
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
            z-index: 1000;
            justify-content: center;
            align-items: center;
        }
        .modal-content {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            width: 90%;
            max-width: 400px;
            max-height: 80vh;
            overflow-y: auto;
        }
        .modal-title {
            margin-top: 0;
            color: #2c3e50;
        }
        .modal-actions {
            display: flex;
            justify-content: flex-end;
            gap: 10px;
            margin-top: 15px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .form-group input, .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .console {
            background-color: #2c3e50;
            color: #ecf0f1;
            padding: 10px;
            border-radius: 5px;
            font-family: monospace;
            font-size: 0.9rem;
            max-height: 200px;
            overflow-y: auto;
            margin-top: 15px;
        }
        .console-entry {
            margin-bottom: 5px;
            border-bottom: 1px solid #34495e;
            padding-bottom: 5px;
        }
        .console-time {
            color: #bdc3c7;
            font-size: 0.8rem;
        }
        .console-message {
            color: white;
        }
        .tab-container {
            display: flex;
            margin-bottom: 10px;
        }
        .tab {
            padding: 10px 15px;
            background-color: #ecf0f1;
            border: none;
            border-radius: 5px 5px 0 0;
            margin-right: 5px;
            cursor: pointer;
        }
        .tab.active {
            background-color: #3498db;
            color: white;
        }
        .tab-content {
            display: none;
        }
        .tab-content.active {
            display: block;
        }
        @media (min-width: 600px) {
            .number-grid {
                grid-template-columns: repeat(10, 1fr);
            }
            .container {
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Selección de Números Móvil</h1>
        
        <div class="tab-container">
            <button class="tab active" data-tab="main">Principal</button>
            <button class="tab" data-tab="console">Consola</button>
        </div>
        
        <div id="main-tab" class="tab-content active">
            <div class="panel">
                <div class="controls">
                    <div class="control-group">
                        <input type="text" class="search-box" placeholder="Buscar número..." id="search-input">
                    </div>
                    <div class="control-group">
                        <button id="clear-search" class="secondary">Limpiar</button>
                    </div>
                </div>
                
                <div class="number-grid" id="number-grid">
                    <!-- Los números del 1 al 100 se generarán aquí -->
                </div>
                
                <div class="controls">
                    <div class="control-group">
                        <button id="name-btn" class="secondary">Asignar Nombres</button>
                    </div>
                    <div class="control-group">
                        <button id="export-btn" class="secondary">Exportar</button>
                    </div>
                    <div class="control-group">
                        <button id="save-btn">Guardar</button>
                    </div>
                    <div class="control-group">
                        <button id="clear-btn" class="danger">Limpiar</button>
                    </div>
                </div>
            </div>
            
            <div class="panel">
                <h2>Números Seleccionados (<span id="selected-count">0</span>)</h2>
                <div class="selected-list" id="selected-list">
                    <!-- Los números seleccionados aparecerán aquí -->
                </div>
            </div>
            
            <div class="panel">
                <h2>Números Marcados (<span id="marked-count">0</span>)</h2>
                <div class="marked-list" id="marked-list">
                    <!-- Los números marcados aparecerán aquí -->
                </div>
            </div>
        </div>
        
        <div id="console-tab" class="tab-content">
            <div class="panel">
                <h2>Consola de Registro</h2>
                <div class="console" id="console">
                    <!-- Los registros de la consola aparecerán aquí -->
                </div>
                <div class="controls">
                    <div class="control-group">
                        <button id="clear-console" class="danger">Limpiar Consola</button>
                    </div>
                    <div class="control-group">
                        <button id="export-console" class="secondary">Exportar Consola</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    <!-- Modal para asignar nombres -->
    <div class="modal" id="name-modal">
        <div class="modal-content">
            <h3 class="modal-title">Asignar Nombres</h3>
            <div id="name-inputs">
                <!-- Los inputs para nombres se generarán aquí -->
            </div>
            <div class="modal-actions">
                <button id="cancel-names" class="danger">Cancelar</button>
                <button id="save-names">Guardar</button>
            </div>
        </div>
    </div>
    
    <!-- Modal para exportar -->
    <div class="modal" id="export-modal">
        <div class="modal-content">
            <h3 class="modal-title">Exportar Datos</h3>
            <div class="form-group">
                <label for="export-format">Formato:</label>
                <select id="export-format" class="search-box">
                    <option value="csv">CSV (Excel)</option>
                    <option value="json">JSON</option>
                    <option value="text">Texto</option>
                </select>
            </div>
            <div class="form-group">
                <label for="export-data">Datos:</label>
                <textarea id="export-data" rows="8" style="width: 100%;" readonly></textarea>
            </div>
            <div class="modal-actions">
                <button id="copy-export" class="secondary">Copiar</button>
                <button id="download-export">Descargar</button>
                <button id="close-export" class="danger">Cerrar</button>
            </div>
        </div>
    </div>

    <script>
        // Variables globales
        let selectedNumbers = new Set();
        let markedNumbers = new Map();
        let numberNames = new Map();
        let consoleLog = [];
        
        // Elementos del DOM
        const numberGrid = document.getElementById('number-grid');
        const selectedList = document.getElementById('selected-list');
        const markedList = document.getElementById('marked-list');
        const consoleElement = document.getElementById('console');
        const saveBtn = document.getElementById('save-btn');
        const clearBtn = document.getElementById('clear-btn');
        const nameBtn = document.getElementById('name-btn');
        const exportBtn = document.getElementById('export-btn');
        const searchInput = document.getElementById('search-input');
        const clearSearchBtn = document.getElementById('clear-search');
        const nameModal = document.getElementById('name-modal');
        const nameInputs = document.getElementById('name-inputs');
        const saveNamesBtn = document.getElementById('save-names');
        const cancelNamesBtn = document.getElementById('cancel-names');
        const exportModal = document.getElementById('export-modal');
        const exportFormat = document.getElementById('export-format');
        const exportData = document.getElementById('export-data');
        const copyExportBtn = document.getElementById('copy-export');
        const downloadExportBtn = document.getElementById('download-export');
        const closeExportBtn = document.getElementById('close-export');
        const selectedCount = document.getElementById('selected-count');
        const markedCount = document.getElementById('marked-count');
        const clearConsoleBtn = document.getElementById('clear-console');
        const exportConsoleBtn = document.getElementById('export-console');
        const tabs = document.querySelectorAll('.tab');
        const tabContents = document.querySelectorAll('.tab-content');

        // Inicialización
        document.addEventListener('DOMContentLoaded', () => {
            generateNumberGrid();
            loadSavedNumbers();
            updateCounters();
            renderConsole();
            
            // Configurar pestañas
            tabs.forEach(tab => {
                tab.addEventListener('click', () => {
                    tabs.forEach(t => t.classList.remove('active'));
                    tabContents.forEach(c => c.classList.remove('active'));
                    
                    tab.classList.add('active');
                    document.getElementById(`${tab.dataset.tab}-tab`).classList.add('active');
                });
            });
        });

        // Event listeners
        saveBtn.addEventListener('click', saveSelection);
        clearBtn.addEventListener('click', clearSelection);
        nameBtn.addEventListener('click', showNameModal);
        exportBtn.addEventListener('click', showExportModal);
        clearSearchBtn.addEventListener('click', clearSearch);
        searchInput.addEventListener('input', filterNumbers);
        saveNamesBtn.addEventListener('click', saveNames);
        cancelNamesBtn.addEventListener('click', () => nameModal.style.display = 'none');
        exportFormat.addEventListener('change', updateExportData);
        copyExportBtn.addEventListener('click', copyExportData);
        downloadExportBtn.addEventListener('click', downloadExport);
        closeExportBtn.addEventListener('click', () => exportModal.style.display = 'none');
        clearConsoleBtn.addEventListener('click', clearConsole);
        exportConsoleBtn.addEventListener('click', exportConsole);

        // Cerrar modales al hacer clic fuera
        window.addEventListener('click', (e) => {
            if (e.target === nameModal) nameModal.style.display = 'none';
            if (e.target === exportModal) exportModal.style.display = 'none';
        });

        // Generar la cuadrícula de números
        function generateNumberGrid() {
            numberGrid.innerHTML = '';
            
            for (let i = 1; i <= 100; i++) {
                const numberCard = document.createElement('div');
                numberCard.className = 'number-card';
                
                const numberElement = document.createElement('div');
                numberElement.className = 'number';
                numberElement.textContent = i;
                
                const nameElement = document.createElement('div');
                nameElement.className = 'number-name';
                nameElement.textContent = numberNames.get(i) || '';
                
                numberCard.appendChild(numberElement);
                numberCard.appendChild(nameElement);
                numberCard.dataset.number = i;
                
                numberCard.addEventListener('click', () => {
                    toggleNumberSelection(i);
                });
                
                numberCard.addEventListener('touchstart', (e) => {
                    e.preventDefault();
                    numberCard.classList.add('touched');
                }, { passive: false });
                
                numberCard.addEventListener('touchend', () => {
                    numberCard.classList.remove('touched');
                    toggleNumberSelection(i);
                });
                
                numberGrid.appendChild(numberCard);
            }
            
            updateNumberGrid();
            logToConsole('Cuadrícula de números generada', 'system');
        }

        // Alternar selección de número
        function toggleNumberSelection(number) {
            if (selectedNumbers.has(number)) {
                selectedNumbers.delete(number);
                logToConsole(`Número ${number} deseleccionado`, 'action');
            } else {
                selectedNumbers.add(number);
                logToConsole(`Número ${number} seleccionado`, 'action');
            }
            
            updateNumberGrid();
            updateSelectedList();
            updateCounters();
        }

        // Actualizar la apariencia de los números en la cuadrícula
        function updateNumberGrid() {
            const allNumbers = document.querySelectorAll('.number-card');
            
            allNumbers.forEach(card => {
                const num = parseInt(card.dataset.number);
                card.classList.remove('selected', 'marked');
                
                if (selectedNumbers.has(num)) {
                    card.classList.add('selected');
                } else if (markedNumbers.has(num)) {
                    card.classList.add('marked');
                }
                
                // Actualizar nombre si existe
                const nameElement = card.querySelector('.number-name');
                nameElement.textContent = numberNames.get(num) || '';
            });
        }

        // Actualizar la lista de seleccionados
        function updateSelectedList() {
            selectedList.innerHTML = '';
            
            if (selectedNumbers.size === 0) {
                selectedList.innerHTML = '<p>No hay números seleccionados</p>';
                return;
            }
            
            // Ordenar los números seleccionados
            const sortedNumbers = Array.from(selectedNumbers).sort((a, b) => a - b);
            
            sortedNumbers.forEach(num => {
                const item = document.createElement('div');
                item.className = 'selected-item';
                item.innerHTML = `
                    <span>${num}${numberNames.get(num) ? `: ${numberNames.get(num)}` : ''}</span>
                    <div class="item-actions">
                        <button class="action-btn secondary" data-number="${num}">Editar</button>
                        <button class="action-btn danger" data-number="${num}">×</button>
                    </div>
                `;
                
                // Agregar eventos para los botones
                item.querySelector('.action-btn.secondary').addEventListener('click', (e) => {
                    e.stopPropagation();
                    selectedNumbers.clear();
                    selectedNumbers.add(num);
                    showNameModal();
                });
                
                item.querySelector('.action-btn.danger').addEventListener('click', (e) => {
                    e.stopPropagation();
                    selectedNumbers.delete(num);
                    updateNumberGrid();
                    updateSelectedList();
                    updateCounters();
                    logToConsole(`Número ${num} removido de selección`, 'action');
                });
                
                selectedList.appendChild(item);
            });
        }

        // Actualizar la lista de marcados
        function updateMarkedList() {
            markedList.innerHTML = '';
            
            if (markedNumbers.size === 0) {
                markedList.innerHTML = '<p>No hay números marcados</p>';
                return;
            }
            
            // Ordenar los números marcados
            const sortedMarked = Array.from(markedNumbers.keys()).sort((a, b) => a - b);
            
            sortedMarked.forEach(num => {
                const item = document.createElement('div');
                item.className = 'marked-item';
                item.innerHTML = `
                    <span>${num}${numberNames.get(num) ? `: ${numberNames.get(num)}` : ''}</span>
                    <div class="item-actions">
                        <button class="action-btn secondary" data-number="${num}">Editar</button>
                        <button class="action-btn danger" data-number="${num}">Eliminar</button>
                    </div>
                `;
                
                // Agregar eventos para los botones
                item.querySelector('.action-btn.secondary').addEventListener('click', (e) => {
                    e.stopPropagation();
                    selectedNumbers.clear();
                    selectedNumbers.add(num);
                    showNameModal();
                });
                
                item.querySelector('.action-btn.danger').addEventListener('click', (e) => {
                    e.stopPropagation();
                    if (confirm(`¿Eliminar el número ${num} de tus marcados?`)) {
                        markedNumbers.delete(num);
                        numberNames.delete(num);
                        saveToLocalStorage();
                        updateMarkedList();
                        updateNumberGrid();
                        updateCounters();
                        logToConsole(`Número ${num} eliminado de marcados`, 'action');
                    }
                });
                
                markedList.appendChild(item);
            });
        }

        // Guardar selección como números marcados
        function saveSelection() {
            if (selectedNumbers.size === 0) {
                alert('No hay números seleccionados para guardar');
                logToConsole('Intento de guardar sin selección', 'warning');
                return;
            }
            
            // Agregar los seleccionados a los marcados
            selectedNumbers.forEach(num => {
                markedNumbers.set(num, true);
                if (!numberNames.has(num)) {
                    numberNames.set(num, '');
                }
            });
            
            logToConsole(`${selectedNumbers.size} números guardados como marcados`, 'action');
            
            // Limpiar selección actual
            selectedNumbers.clear();
            
            // Actualizar la vista
            updateNumberGrid();
            updateSelectedList();
            updateMarkedList();
            
            // Guardar en localStorage
            saveToLocalStorage();
            
            updateCounters();
        }

        // Limpiar toda la selección
        function clearSelection() {
            if (confirm('¿Estás seguro de que quieres limpiar todos los números seleccionados y marcados?')) {
                selectedNumbers.clear();
                markedNumbers.clear();
                numberNames.clear();
                localStorage.removeItem('numberAppData');
                updateNumberGrid();
                updateSelectedList();
                updateMarkedList();
                updateCounters();
                logToConsole('Todos los datos fueron limpiados', 'action');
            }
        }

        // Cargar números guardados previamente
        function loadSavedNumbers() {
            const saved = localStorage.getItem('numberAppData');
            if (saved) {
                try {
                    const data = JSON.parse(saved);
                    markedNumbers = new Map(data.markedNumbers);
                    numberNames = new Map(data.numberNames);
                    updateMarkedList();
                    updateNumberGrid();
                    logToConsole('Datos cargados desde almacenamiento', 'system');
                } catch (e) {
                    logToConsole('Error al cargar datos: ' + e.message, 'error');
                }
            } else {
                logToConsole('No se encontraron datos guardados', 'system');
            }
        }

        // Guardar datos en localStorage
        function saveToLocalStorage() {
            const data = {
                markedNumbers: Array.from(markedNumbers.entries()),
                numberNames: Array.from(numberNames.entries())
            };
            localStorage.setItem('numberAppData', JSON.stringify(data));
            logToConsole('Datos guardados en almacenamiento', 'system');
        }

        // Filtrar números según búsqueda
        function filterNumbers() {
            const searchTerm = searchInput.value.trim().toLowerCase();
            
            if (!searchTerm) {
                document.querySelectorAll('.number-card').forEach(card => {
                    card.style.display = 'flex';
                });
                return;
            }
            
            document.querySelectorAll('.number-card').forEach(card => {
                const num = card.dataset.number;
                const name = numberNames.get(parseInt(num)) || '';
                
                if (num.includes(searchTerm) || name.toLowerCase().includes(searchTerm)) {
                    card.style.display = 'flex';
                } else {
                    card.style.display = 'none';
                }
            });
            
            logToConsole(`Búsqueda realizada: "${searchTerm}"`, 'action');
        }

        // Limpiar búsqueda
        function clearSearch() {
            searchInput.value = '';
            filterNumbers();
            logToConsole('Búsqueda limpiada', 'action');
        }

        // Mostrar modal para asignar nombres
        function showNameModal() {
            if (selectedNumbers.size === 0) {
                alert('Selecciona al menos un número para asignarle nombre');
                logToConsole('Intento de asignar nombres sin selección', 'warning');
                return;
            }
            
            nameInputs.innerHTML = '';
            
            // Ordenar los números seleccionados
            const sortedNumbers = Array.from(selectedNumbers).sort((a, b) => a - b);
            
            sortedNumbers.forEach(num => {
                const group = document.createElement('div');
                group.className = 'form-group';
                
                const label = document.createElement('label');
                label.textContent = `Nombre para ${num}:`;
                
                const input = document.createElement('input');
                input.type = 'text';
                input.dataset.number = num;
                input.value = numberNames.get(num) || '';
                input.placeholder = `Ej: Mi número ${num}`;
                
                group.appendChild(label);
                group.appendChild(input);
                nameInputs.appendChild(group);
            });
            
            nameModal.style.display = 'flex';
            logToConsole('Modal de nombres mostrado', 'system');
        }

        // Guardar nombres asignados
        function saveNames() {
            const inputs = nameInputs.querySelectorAll('input');
            let namesUpdated = 0;
            
            inputs.forEach(input => {
                const num = parseInt(input.dataset.number);
                const name = input.value.trim();
                
                if (name) {
                    numberNames.set(num, name);
                    namesUpdated++;
                } else {
                    numberNames.delete(num);
                }
            });
            
            saveToLocalStorage();
            nameModal.style.display = 'none';
            updateNumberGrid();
            updateSelectedList();
            updateMarkedList();
            logToConsole(`${namesUpdated} nombres asignados/actualizados`, 'action');
        }

        // Mostrar modal de exportación
        function showExportModal() {
            if (markedNumbers.size === 0) {
                alert('No hay números marcados para exportar');
                logToConsole('Intento de exportar sin datos', 'warning');
                return;
            }
            
            exportModal.style.display = 'flex';
            updateExportData();
            logToConsole('Modal de exportación mostrado', 'system');
        }

        // Actualizar datos de exportación según formato seleccionado
        function updateExportData() {
            const format = exportFormat.value;
            let data = '';
            
            // Ordenar los números marcados
            const sortedMarked = Array.from(markedNumbers.keys()).sort((a, b) => a - b);
            
            switch (format) {
                case 'csv':
                    data = 'Número,Nombre\n';
                    sortedMarked.forEach(num => {
                        data += `${num},"${numberNames.get(num) || ''}"\n`;
                    });
                    break;
                    
                case 'json':
                    const jsonData = {};
                    sortedMarked.forEach(num => {
                        jsonData[num] = numberNames.get(num) || '';
                    });
                    data = JSON.stringify(jsonData, null, 2);
                    break;
                    
                case 'text':
                    sortedMarked.forEach(num => {
                        data += `Número ${num}: ${numberNames.get(num) || '(sin nombre)'}\n`;
                    });
                    break;
            }
            
            exportData.value = data;
        }

        // Copiar datos exportados al portapapeles
        function copyExportData() {
            exportData.select();
            document.execCommand('copy');
            alert('Datos copiados al portapapeles');
            logToConsole('Datos exportados copiados al portapapeles', 'action');
        }

        // Descargar archivo exportado
        function downloadExport() {
            const format = exportFormat.value;
            const data = exportData.value;
            let filename = 'numeros_marcados';
            let mimeType = 'text/plain';
            
            switch (format) {
                case 'csv':
                    filename += '.csv';
                    mimeType = 'text/csv';
                    break;
                case 'json':
                    filename += '.json';
                    mimeType = 'application/json';
                    break;
                case 'text':
                    filename += '.txt';
                    break;
            }
            
            const blob = new Blob([data], { type: `${mimeType};charset=utf-8;` });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = filename;
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
            
            logToConsole(`Datos exportados descargados como ${filename}`, 'action');
        }

        // Actualizar contadores
        function updateCounters() {
            selectedCount.textContent = selectedNumbers.size;
            markedCount.textContent = markedNumbers.size;
        }

        // Funciones de la consola
        function logToConsole(message, type = 'info') {
            const now = new Date();
            const timeString = now.toLocaleTimeString();
            const logEntry = {
                time: timeString,
                message: message,
                type: type
            };
            
            consoleLog.push(logEntry);
            renderConsole();
            
            // También mostrar en la consola del navegador
            switch(type) {
                case 'error': console.error(message); break;
                case 'warning': console.warn(message); break;
                default: console.log(message);
            }
        }

        function renderConsole() {
            consoleElement.innerHTML = '';
            
            if (consoleLog.length === 0) {
                consoleElement.innerHTML = '<div class="console-entry">No hay registros en la consola</div>';
                return;
            }
            
            // Mostrar los últimos 50 registros
            const recentLogs = consoleLog.slice(-50);
            
            recentLogs.forEach(entry => {
                const entryElement = document.createElement('div');
                entryElement.className = 'console-entry';
                
                const timeElement = document.createElement('div');
                timeElement.className = 'console-time';
                timeElement.textContent = entry.time;
                
                const messageElement = document.createElement('div');
                messageElement.className = 'console-message';
                messageElement.textContent = entry.message;
                
                // Color según tipo
                switch(entry.type) {
                    case 'error':
                        messageElement.style.color = '#e74c3c';
                        break;
                    case 'warning':
                        messageElement.style.color = '#f39c12';
                        break;
                    case 'action':
                        messageElement.style.color = '#2ecc71';
                        break;
                    case 'system':
                        messageElement.style.color = '#3498db';
                        break;
                }
                
                entryElement.appendChild(timeElement);
                entryElement.appendChild(messageElement);
                consoleElement.appendChild(entryElement);
            });
            
            // Auto-scroll al final
            consoleElement.scrollTop = consoleElement.scrollHeight;
        }

        function clearConsole() {
            consoleLog = [];
            renderConsole();
            logToConsole('Consola limpiada', 'system');
        }

        function exportConsole() {
            if (consoleLog.length === 0) {
                alert('No hay registros en la consola para exportar');
                return;
            }
            
            let data = 'Registros de la Consola:\n\n';
            consoleLog.forEach(entry => {
                data += `[${entry.time}] ${entry.message}\n`;
            });
            
            const blob = new Blob([data], { type: 'text/plain;charset=utf-8;' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'consola_numeros.txt';
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
            
            logToConsole('Registros de consola exportados', 'action');
        }
    </script>
</body>
</html>
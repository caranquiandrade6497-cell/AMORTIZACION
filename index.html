<!DOCTYPE html>
<html lang="es" class="h-full bg-slate-950">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SIA - Simulador de Intereses Automatizado</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;700&family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap');
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
        .code-font { font-family: 'Fira Code', monospace; }
        ::-webkit-scrollbar { width: 6px; height: 6px; }
        ::-webkit-scrollbar-track { background: #0f172a; }
        ::-webkit-scrollbar-thumb { background: #334155; border-radius: 3px; }
        ::-webkit-scrollbar-thumb:hover { background: #475569; }
    </style>
</head>
<body class="h-full text-slate-100 flex flex-col">

    <header class="border-b border-slate-800 bg-slate-900/80 backdrop-blur-md sticky top-0 z-50 px-6 py-4">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-4">
            <div class="flex items-center gap-3">
                <div class="p-2.5 bg-emerald-500/10 rounded-xl border border-emerald-500/30 text-emerald-400">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                    </svg>
                </div>
                <div>
                    <h1 class="text-xl font-extrabold tracking-tight text-white flex items-center gap-2">
                        SIA <span class="text-xs font-semibold px-2 py-0.5 rounded bg-emerald-500/20 text-emerald-400 border border-emerald-500/30">v2.0 PRO</span>
                    </h1>
                    <p class="text-xs text-slate-400">Engineered Interest & Automated Amortization Generator</p>
                </div>
            </div>
            <div class="flex items-center gap-2 text-xs text-slate-400 font-medium">
                <span class="inline-block w-2.5 h-2.5 rounded-full bg-emerald-500 animate-pulse"></span>
                Sistemas Listos y Compilando
            </div>
        </div>
    </header>

    <main class="flex-1 max-w-7xl w-full mx-auto p-4 sm:p-6 lg:p-8 grid grid-cols-1 lg:grid-cols-12 gap-8">
        <section class="lg:col-span-4 flex flex-col gap-6">
            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 shadow-xl">
                <h2 class="text-lg font-bold text-white mb-5 flex items-center gap-2 border-b border-slate-800 pb-3">
                    <span class="text-emerald-400">01.</span> Parámetros Financieros
                </h2>
                
                <div class="flex flex-col gap-4">
                    <div>
                        <label for="inputActivo" class="block text-xs font-semibold text-slate-300 uppercase tracking-wider mb-2">Valor del Activo (Capital)</label>
                        <div class="relative rounded-lg shadow-sm">
                            <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                                <span class="text-slate-500 sm:text-sm">$</span>
                            </div>
                            <input type="number" id="inputActivo" value="50000" min="100" step="100" class="block w-full pl-8 pr-4 py-3 bg-slate-950 border border-slate-800 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 focus:border-transparent text-white font-semibold placeholder-slate-600 transition">
                        </div>
                    </div>

                    <div>
                        <label for="inputPlazo" class="block text-xs font-semibold text-slate-300 uppercase tracking-wider mb-2">Plazo del Crédito</label>
                        <div class="relative rounded-lg shadow-sm">
                            <input type="number" id="inputPlazo" value="12" min="1" max="360" class="block w-full px-4 py-3 bg-slate-950 border border-slate-800 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 focus:border-transparent text-white font-semibold transition">
                            <div class="absolute inset-y-0 right-0 pr-3 flex items-center pointer-events-none">
                                <span class="text-slate-500 sm:text-sm">Meses</span>
                            </div>
                        </div>
                    </div>

                    <div>
                        <label for="inputInteres" class="block text-xs font-semibold text-slate-300 uppercase tracking-wider mb-2">Tasa de Interés Anual (T.N.A.)</label>
                        <div class="relative rounded-lg shadow-sm">
                            <input type="number" id="inputInteres" value="15" min="0.1" max="100" step="0.01" class="block w-full px-4 py-3 bg-slate-950 border border-slate-800 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 focus:border-transparent text-white font-semibold transition">
                            <div class="absolute inset-y-0 right-0 pr-3 flex items-center pointer-events-none">
                                <span class="text-slate-500 sm:text-sm">% EA</span>
                            </div>
                        </div>
                    </div>

                    <div>
                        <label for="selectSistema" class="block text-xs font-semibold text-slate-300 uppercase tracking-wider mb-2">Fórmula de Amortización</label>
                        <select id="selectSistema" class="block w-full px-4 py-3 bg-slate-950 border border-slate-800 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 focus:border-transparent text-white font-semibold transition">
                            <option value="frances">Sistema Francés (Cuota Constante)</option>
                            <option value="regresivo">Sistema Regresivo/Alemán (Capital Fijo)</option>
                            <option value="lineal">Sistema Lineal/Simple (Flat Rate)</option>
                        </select>
                    </div>

                    <button onclick="procesarCalculos()" class="w-full mt-2 bg-gradient-to-r from-emerald-500 to-teal-600 hover:from-emerald-400 hover:to-teal-500 text-slate-950 font-bold py-4 px-6 rounded-xl shadow-lg shadow-emerald-500/10 transition-all transform hover:-translate-y-0.5 active:translate-y-0 flex items-center justify-center gap-2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM9.555 7.168A1 1 0 008 8v4a1 1 0 001.555.832l3-2a1 1 0 000-1.664l-3-2z" clip-rule="evenodd" />
                        </svg>
                        COMPILAR CÁLCULO
                    </button>
                </div>
            </div>

            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6">
                <h3 class="text-sm font-bold text-white mb-3 uppercase tracking-wider text-slate-400">Arquitectura Seleccionada</h3>
                <div id="sistemaInfo" class="text-sm text-slate-400 leading-relaxed"></div>
            </div>
        </section>

        <section class="lg:col-span-8 flex flex-col gap-6">
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                <div class="bg-slate-900 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between">
                    <span class="text-xs font-semibold text-slate-400 uppercase tracking-wider">Cuota Mensual</span>
                    <span id="metaCuota" class="text-2xl font-extrabold text-white mt-2">-</span>
                    <span id="metaCuotaSub" class="text-xs text-slate-500 mt-1">Estructura variable</span>
                </div>
                <div class="bg-slate-900 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between">
                    <span class="text-xs font-semibold text-slate-400 uppercase tracking-wider">Intereses Totales</span>
                    <span id="metaTotalIntereses" class="text-2xl font-extrabold text-amber-400 mt-2">$0.00</span>
                    <span id="metaInteresRatio" class="text-xs text-slate-500 mt-1">0% del préstamo</span>
                </div>
                <div class="bg-slate-900 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between">
                    <span class="text-xs font-semibold text-slate-400 uppercase tracking-wider">Desembolso Total</span>
                    <span id="metaDesembolsoTotal" class="text-2xl font-extrabold text-emerald-400 mt-2">$0.00</span>
                    <span class="text-xs text-slate-500 mt-1">Capital + Interés</span>
                </div>
            </div>

            <div class="bg-slate-900 border border-slate-800 rounded-2xl flex flex-col overflow-hidden">
                <div class="flex border-b border-slate-800 bg-slate-950/60 p-2 gap-1">
                    <button onclick="cambiarTab('tab-tabla')" id="btn-tab-tabla" class="flex-1 py-2.5 px-4 rounded-xl text-sm font-semibold transition-all duration-200 bg-slate-800 text-white">Tabla de Pagos</button>
                    <button onclick="cambiarTab('tab-grafica')" id="btn-tab-grafica" class="flex-1 py-2.5 px-4 rounded-xl text-sm font-semibold transition-all duration-200 text-slate-400 hover:text-white">Curva de Amortización</button>
                    <button onclick="cambiarTab('tab-codigo')" id="btn-tab-codigo" class="flex-1 py-2.5 px-4 rounded-xl text-sm font-semibold transition-all duration-200 text-slate-400 hover:text-white flex items-center justify-center gap-2">
                        <span>Generar Código</span>
                        <span class="px-1.5 py-0.5 rounded text-[10px] bg-emerald-500/20 text-emerald-400 font-bold border border-emerald-500/20">DEV</span>
                    </button>
                </div>

                <div class="p-6">
                    <div id="tab-tabla" class="tab-content">
                        <div class="flex justify-between items-center mb-4">
                            <h3 class="font-bold text-white text-base">Proyección de Pagos</h3>
                            <button onclick="exportarCSV()" class="text-xs font-medium text-emerald-400 hover:text-emerald-300 flex items-center gap-1 bg-emerald-500/10 border border-emerald-500/20 px-3 py-1.5 rounded-lg transition">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 10v6m0 0l-3-3m3 3l3-3m2 8H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                                </svg>
                                Exportar .CSV
                            </button>
                        </div>
                        <div class="overflow-x-auto rounded-xl border border-slate-800 max-h-[380px] overflow-y-auto">
                            <table class="w-full text-left border-collapse text-sm">
                                <thead class="bg-slate-950 sticky top-0 border-b border-slate-800">
                                    <tr>
                                        <th class="p-4 font-bold text-slate-300 text-center w-16">Período</th>
                                        <th class="p-4 font-bold text-slate-300 text-right">Cuota Total</th>
                                        <th class="p-4 font-bold text-slate-300 text-right">Intereses</th>
                                        <th class="p-4 font-bold text-slate-300 text-right">Capital Amortizado</th>
                                        <th class="p-4 font-bold text-slate-300 text-right">Saldo Deudor</th>
                                    </tr>
                                </thead>
                                <tbody id="tbodyAmortizacion" class="divide-y divide-slate-800/55"></tbody>
                            </table>
                        </div>
                    </div>

                    <div id="tab-grafica" class="tab-content hidden">
                        <h3 class="font-bold text-white text-base mb-4">Composición Acumulada del Pago</h3>
                        <div class="w-full h-[320px] relative">
                            <canvas id="chartAmortizacion"></canvas>
                        </div>
                    </div>

                    <div id="tab-codigo" class="tab-content hidden">
                        <div class="flex flex-col gap-4">
                            <div class="flex justify-between items-center">
                                <h3 class="font-bold text-white text-base">Automatización de Backend</h3>
                                <div class="flex bg-slate-950 border border-slate-800 rounded-lg p-1 gap-1">
                                    <button onclick="seleccionarLenguaje('js')" id="btn-lang-js" class="px-3 py-1 rounded text-xs font-semibold bg-emerald-500 text-slate-950 transition-all">JavaScript</button>
                                    <button onclick="seleccionarLenguaje('py')" id="btn-lang-py" class="px-3 py-1 rounded text-xs font-semibold text-slate-400 hover:text-white transition-all">Python</button>
                                    <button onclick="seleccionarLenguaje('sql')" id="btn-lang-sql" class="px-3 py-1 rounded text-xs font-semibold text-slate-400 hover:text-white transition-all">PostgreSQL CTE</button>
                                </div>
                            </div>
                            <p class="text-xs text-slate-400">Este bloque de código está parametrizado dinámicamente con los valores configurados a la izquierda.</p>
                            <div class="relative group">
                                <pre class="bg-slate-950 border border-slate-800 rounded-xl p-5 overflow-x-auto text-xs code-font text-emerald-400 max-h-[300px] overflow-y-auto"><code id="bloqueCodigo"></code></pre>
                                <button onclick="copiarCodigo()" class="absolute top-3 right-3 bg-slate-800 hover:bg-slate-700 text-white font-medium py-1.5 px-3 rounded-lg text-xs flex items-center gap-1 transition-all">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 5H6a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2v-1M8 5a2 2 0 002 2h2a2 2 0 002-2M8 5a2 2 0 012-2h2a2 2 0 012 2m0 0h2a2 2 0 012 2v3m2 4H10m0 0l3-3m-3 3l3 3" />
                                    </svg>
                                    Copiar
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="border-t border-slate-800 bg-slate-900/60 py-6 px-6 text-center text-xs text-slate-500">
        <p>© 2026 Sistema de Ingeniería de Amortización Automatizada. Licencia MIT.</p>
    </footer>

    <div id="toast" class="fixed bottom-5 right-5 bg-emerald-500 text-slate-950 px-4 py-3 rounded-xl font-bold text-sm shadow-xl flex items-center gap-2 transform translate-y-20 opacity-0 transition-all duration-300 pointer-events-none">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
        </svg>
        <span id="toastText"></span>
    </div>

    <script>
        let globalAmortizationData = [];
        let chartInstance = null;
        let selectedLanguage = 'js';

        const infoSistemas = {
            frances: { titulo: "Sistema Francés", desc: "Se basa en amortización progresiva. Las cuotas son constantes durante todo el ciclo de vida del crédito. Los intereses se calculan mensualmente sobre el saldo insoluto." },
            regresivo: { titulo: "Sistema Regresivo (Alemán)", desc: "Modelo de amortización de capital fijo. Las cuotas mensuales son variables y regresivas (decrecientes), ya que el interés disminuye sobre saldo." },
            lineal: { titulo: "Sistema Lineal (Flat Rate)", desc: "El interés se calcula de forma constante sobre el capital original del activo para cada período. Cuotas e intereses lineales perfectos." }
        };

        window.addEventListener('DOMContentLoaded', () => { procesarCalculos(); });

        function cambiarTab(tabId) {
            document.querySelectorAll('.tab-content').forEach(tab => tab.classList.add('hidden'));
            document.getElementById(tabId).classList.remove('hidden');
            ['btn-tab-tabla', 'btn-tab-grafica', 'btn-tab-codigo'].forEach(id => {
                document.getElementById(id).className = "flex-1 py-2.5 px-4 rounded-xl text-sm font-semibold transition-all duration-200 text-slate-400 hover:text-white";
            });
            document.getElementById('btn-' + tabId).className = "flex-1 py-2.5 px-4 rounded-xl text-sm font-semibold transition-all duration-200 bg-slate-800 text-white";
            if (tabId === 'tab-grafica') { renderizarGrafica(); }
        }

        function formatCurrency(val) { return new Intl.NumberFormat('es-US', { style: 'currency', currency: 'USD' }).format(val); }

        function procesarCalculos() {
            const activo = parseFloat(document.getElementById('inputActivo').value);
            const plazo = parseInt(document.getElementById('inputPlazo').value);
            const interesAnual = parseFloat(document.getElementById('inputInteres').value);
            const sistema = document.getElementById('selectSistema').value;

            if (isNaN(activo) || activo <= 0 || isNaN(plazo) || plazo <= 0 || isNaN(interesAnual) || interesAnual < 0) {
                mostrarToast("Error en los parámetros ingresados.", true);
                return;
            }

            document.getElementById('sistemaInfo').innerHTML = `<strong class="text-white block mb-1 text-sm">${infoSistemas[sistema].titulo}</strong><p class="text-xs text-slate-400">${infoSistemas[sistema].desc}</p>`;

            const tasaMensual = (interesAnual / 100) / 12;
            let saldo = activo;
            globalAmortizationData = [];
            let totalInteres = 0;

            if (sistema === 'frances') {
                let cuotaMensual = tasaMensual === 0 ? activo / plazo : activo * (tasaMensual * Math.pow(1 + tasaMensual, plazo)) / (Math.pow(1 + tasaMensual, plazo) - 1);
                for (let i = 1; i <= plazo; i++) {
                    const interes = saldo * tasaMensual;
                    const amortizacion = cuotaMensual - interes;
                    saldo -= amortizacion;
                    totalInteres += interes;
                    globalAmortizationData.push({ periodo: i, cuota: cuotaMensual, interes: interes, amortizacion: amortizacion, saldo: Math.max(0, saldo) });
                }
                document.getElementById('metaCuota').innerText = formatCurrency(cuotaMensual);
                document.getElementById('metaCuotaSub').innerText = "Fija y constante";
            } else if (sistema === 'regresivo') {
                const amortizacionFija = activo / plazo;
                for (let i = 1; i <= plazo; i++) {
                    const interes = saldo * tasaMensual;
                    const cuota = amortizacionFija + interes;
                    saldo -= amortizacionFija;
                    totalInteres += interes;
                    globalAmortizationData.push({ periodo: i, cuota: cuota, interes: interes, amortizacion: amortizacionFija, saldo: Math.max(0, saldo) });
                }
                document.getElementById('metaCuota').innerText = `${formatCurrency(globalAmortizationData[plazo - 1].cuota)} a ${formatCurrency(globalAmortizationData[0].cuota)}`;
                document.getElementById('metaCuotaSub').innerText = "Variable decreciente";
            } else if (sistema === 'lineal') {
                const interesFijo = activo * tasaMensual;
                const amortizacionFija = activo / plazo;
                const cuotaConstante = amortizacionFija + interesFijo;
                for (let i = 1; i <= plazo; i++) {
                    saldo -= amortizacionFija;
                    totalInteres += interesFijo;
                    globalAmortizationData.push({ periodo: i, cuota: cuotaConstante, interes: interesFijo, amortizacion: amortizacionFija, saldo: Math.max(0, saldo) });
                }
                document.getElementById('metaCuota').innerText = formatCurrency(cuotaConstante);
                document.getElementById('metaCuotaSub').innerText = "Fija (Interés Flat)";
            }

            document.getElementById('metaTotalIntereses').innerText = formatCurrency(totalInteres);
            document.getElementById('metaDesembolsoTotal').innerText = formatCurrency(activo + totalInteres);
            document.getElementById('metaInteresRatio').innerText = `${((totalInteres / activo) * 100).toFixed(1)}% del activo`;

            renderizarTabla();
            actualizarCodigo();
            if (!document.getElementById('tab-grafica').classList.contains('hidden')) { renderizarGrafica(); }
        }

        function renderizarTabla() {
            const tbody = document.getElementById('tbodyAmortizacion');
            tbody.innerHTML = '';
            globalAmortizationData.forEach(row => {
                const tr = document.createElement('tr');
                tr.className = "hover:bg-slate-900/60 transition-colors";
                tr.innerHTML = `
                    <td class="p-4 text-center text-slate-400 font-semibold border-r border-slate-800/40">${row.periodo}</td>
                    <td class="p-4 text-right font-bold text-white">${formatCurrency(row.cuota)}</td>
                    <td class="p-4 text-right text-amber-400/90 font-medium">${formatCurrency(row.interes)}</td>
                    <td class="p-4 text-right text-sky-400 font-medium">${formatCurrency(row.amortizacion)}</td>
                    <td class="p-4 text-right text-slate-300 font-medium">${formatCurrency(row.saldo)}</td>`;
                tbody.appendChild(tr);
            });
        }

        function renderizarGrafica() {
            const ctx = document.getElementById('chartAmortizacion').getContext('2d');
            if (chartInstance) { chartInstance.destroy(); }
            chartInstance = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: globalAmortizationData.map(d => `Mes ${d.periodo}`),
                    datasets: [
                        { label: 'Amortización ($)', data: globalAmortizationData.map(d => d.amortizacion), backgroundColor: 'rgba(56, 189, 248, 0.75)', stack: 'Stack 0' },
                        { label: 'Intereses ($)', data: globalAmortizationData.map(d => d.interes), backgroundColor: 'rgba(251, 191, 36, 0.75)', stack: 'Stack 0' },
                        { label: 'Saldo Deuda ($)', data: globalAmortizationData.map(d => d.saldo), type: 'line', borderColor: 'rgba(16, 185, 129, 1)', borderWidth: 3, fill: false, yAxisID: 'y2' }
                    ]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        x: { stacked: true, ticks: { color: '#94a3b8' } },
                        y: { stacked: true, ticks: { color: '#94a3b8' } },
                        y2: { position: 'right', ticks: { color: '#10b981' } }
                    },
                    plugins: { legend: { labels: { color: '#94a3b8' } } }
                }
            });
        }

        function exportarCSV() {
            let csv = "Periodo,Cuota Total,Intereses,Capital Amortizado,Saldo Deudor\n";
            globalAmortizationData.forEach(r => { csv += `${r.periodo},${r.cuota.toFixed(2)},${r.interes.toFixed(2)},${r.amortizacion.toFixed(2)},${r.saldo.toFixed(2)}\n`; });
            const link = document.createElement("a");
            link.setAttribute("href", encodeURI("data:text/csv;charset=utf-8," + csv));
            link.setAttribute("download", `Amortizacion_${document.getElementById('selectSistema').value}.csv`);
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);
            mostrarToast("Archivo .CSV exportado con éxito");
        }

        function seleccionarLenguaje(lang) {
            selectedLanguage = lang;
            ['js', 'py', 'sql'].forEach(l => { document.getElementById('btn-lang-' + l).className = "px-3 py-1 rounded text-xs font-semibold text-slate-400 hover:text-white transition-all"; });
            document.getElementById('btn-lang-' + lang).className = "px-3 py-1 rounded text-xs font-semibold bg-emerald-500 text-slate-950 transition-all";
            actualizarCodigo();
        }

        function actualizarCodigo() {
            const activo = parseFloat(document.getElementById('inputActivo').value) || 0;
            const plazo = parseInt(document.getElementById('inputPlazo').value) || 0;
            const interesAnual = parseFloat(document.getElementById('inputInteres').value) || 0;
            const sistema = document.getElementById('selectSistema').value;
            const tMensual = ((interesAnual / 100) / 12).toFixed(6);
            let codigo = '';

            if (selectedLanguage === 'js') {
                codigo = `// Algoritmo JavaScript para sistema: ${sistema.toUpperCase()}\nconst capital = ${activo}, meses = ${plazo}, interesAnual = ${interesAnual};\nconst tasaMensual = (interesAnual / 100) / 12;\nlet saldo = capital;\nconst cronograma = [];\n// ... Lógica matemática del loop calculada dinámicamente en UI`;
            } else if (selectedLanguage === 'py') {
                codigo = `# Script en Python para sistema: ${sistema.toUpperCase()}\ndef simular(capital=${activo}, meses=${plazo}, tasa_anual=${interesAnual}):\n    tasa_mensual = (tasa_anual / 100) / 12\n    # Executing calculation loop...`;
            } else if (selectedLanguage === 'sql') {
                codigo = `-- SQL Recursive CTE para sistema: ${sistema.toUpperCase()}\nWITH RECURSIVE Amortizacion AS (\n    SELECT 0 AS periodo, CAST(${activo} AS NUMERIC(15,2)) AS saldo_deudor\n    UNION ALL\n    SELECT periodo + 1, CAST(saldo_deudor - (${activo}/${plazo}) AS NUMERIC(15,2)) FROM Amortizacion WHERE periodo < ${plazo}\n)\nSELECT * FROM Amortizacion;`;
            }
            document.getElementById('bloqueCodigo').textContent = codigo;
        }

        function copiarCodigo() {
            const dummy = document.createElement("textarea");
            document.body.appendChild(dummy);
            dummy.value = document.getElementById('bloqueCodigo').textContent;
            dummy.select();
            document.execCommand("copy");
            document.body.removeChild(dummy);
            mostrarToast("¡Código copiado al portapapeles!");
        }

        function mostrarToast(m, e = false) {
            const t = document.getElementById('toast'), ts = document.getElementById('toastText');
            ts.innerText = m;
            if(e) { t.classList.replace('bg-emerald-500', 'bg-rose-500'); t.classList.replace('text-slate-950', 'text-white'); }
            else { t.classList.replace('bg-rose-500', 'bg-emerald-500'); t.classList.replace('text-white', 'text-slate-950'); }
            t.classList.remove('translate-y-20', 'opacity-0');
            setTimeout(() => { t.classList.add('translate-y-20', 'opacity-0'); }, 3000);
        }
    </script>
</body>
</html>
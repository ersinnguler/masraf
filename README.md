[index.html](https://github.com/user-attachments/files/26243359/index.html)
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ersin | Masraf Envanteri</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        body { background-color: #0f172a; color: #e2e8f0; font-family: 'Inter', sans-serif; }
        .glass-card { background: rgba(30, 41, 59, 0.7); border: 1px solid #334155; backdrop-filter: blur(10px); }
        .accent-cyan { background-color: #22d3ee; color: #0f172a; }
        .accent-cyan:hover { background-color: #06b6d4; transform: translateY(-1px); }
        input, select { background: #1e293b !important; border: 1px solid #475569 !important; color: white !important; }
        input:focus { border-color: #22d3ee !important; outline: none; }
    </style>
</head>
<body class="p-4 md:p-10 min-h-screen">

    <div class="max-w-4xl mx-auto">
        <div class="flex justify-between items-end mb-8">
            <div>
                <h1 class="text-3xl font-black tracking-tight text-slate-400 italic">MASRAF<span class="text-cyan-400 not-italic">ENVANTERİ</span></h1>
                <p class="text-[10px] text-slate-500 uppercase tracking-widest mt-1">Sistem Aktif | Ersin</p>
            </div>
            <div class="text-right">
                <span class="block text-[10px] text-slate-500 uppercase">Toplam Harcama</span>
                <span id="totalDisplay" class="text-2xl font-bold text-cyan-400">0.00 ₺</span>
            </div>
        </div>

        <div class="glass-card p-6 rounded-2xl mb-8 shadow-2xl border-t-2 border-t-cyan-500">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                <input type="text" id="desc"

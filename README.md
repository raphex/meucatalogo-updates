# 📁 MeuCatálogo

# ➡️ [`DOWNLOAD`](https://github.com/raphex/meucatalogo-updates/releases/download/v1.0.2/MeuCatalogo_Setup.exe)

**MeuCatálogo** é um aplicativo de desktop desenvolvido para **catalogar, organizar e localizar arquivos rapidamente** em seu computador.

Ele cria um banco de dados local com os metadados dos seus arquivos, permitindo buscas instantâneas, filtros avançados e identificação de arquivos duplicados.

## 🚀 Funcionalidades

✅ Catalogação rápida de pastas
✅ Banco de dados local (SQLite)
✅ Busca em tempo real
✅ Filtro por:

* tipo de arquivo
* extensão
* tamanho
* data
  ✅ Identificação de arquivos duplicados (por hash)
  ✅ Painel de duplicados
  ✅ Barra de progresso com % e tempo restante
  ✅ Sistema de atualização automática via GitHub

## 🖥️ Como instalar

### Opção 1 — Versão instalada

1. Baixe o instalador na página de **Releases**
2. Execute o instalador
3. Abra o **MeuCatálogo**

### Opção 2 — Executar pelo código

```bash
git clone https://github.com/raphex/meucatalogo
cd meucatalogo
pip install -r requirements.txt
python catalogador_gui.py
```

---

## 🔄 Atualizações automáticas

O aplicativo verifica atualizações automaticamente através de um servidor GitHub.

O sistema valida:

✅ versão
✅ integridade (hash SHA256)
✅ atualização silenciosa

---

## 🛠️ Tecnologias utilizadas

* Python
* Tkinter
* SQLite
* PyInstaller
* GitHub (sistema de updates)

---

## 🧩 Estrutura do projeto

```
MeuCatalogo/
├── catalogador_gui.py
├── updater.py
├── update.json
├── requirements.txt
├── meucatalogo.ico
└── README.md
```

---

## 📌 Roadmap

* [ ] Backup automático do banco
* [ ] Exportar relatórios (CSV / Excel)
* [ ] Modo noturno
* [ ] Indexação por conteúdo
* [ ] Integração com nuvem

---

## 👤 Autor

Desenvolvido por **Raphael Oliveira**

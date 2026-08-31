# MDReader

A single-file Markdown editor and reader PWA — write/edit in the left pane, live-rendered preview on the right. Built with pinned, self-hosted libraries (markdown-it 14, highlight.js 11, DOMPurify 3); no build step. Installable to a phone home screen.

**Language:** [العربية](#العربية) · [中文](#中文) · [English](#english) · [Français](#français) · [Русский](#русский) · [Español](#español)

---

## English

A single-file Markdown editor + reader web app: edit in the left pane, live-rendered preview on the right. All rendering runs locally in the browser. Built with pinned, self-hosted libraries (markdown-it 14, highlight.js 11, DOMPurify 3) — no build step, installable to a phone home screen (PWA).

**Live:** https://agileaq.github.io/MDReader/

### Features

- **Live preview** — left editor, right rendered view, re-render as you type
- **Open / Save as** — load a local `.md` file, or download current content as `document.md`
- **Reader mode** — hides the editor for a distraction-free reading view (preference remembered)
- **Drag & drop** — drop a `.md` file anywhere to open it
- **Auto-save** — content persists in localStorage; reload and continue where you left off
- **Syntax highlighting** — fenced code blocks via highlight.js, GitHub-style theme
- **XSS-safe** — rendered HTML is sanitized with DOMPurify
- **GFM extras** — tables, strikethrough, and task lists (`- [x]` → checkbox)
- **PWA / offline** — installable to the home screen (iOS: Safari → Share → Add to Home Screen)

### Notes

- The renderer is GitHub-flavored: tables, strikethrough and task-list checkboxes are enabled.
- Content is stored locally per device only; nothing is uploaded anywhere.

---

## 中文

单文件 Markdown 编辑 + 阅读器网页应用：左侧编辑、右侧实时渲染预览，全部渲染都在浏览器本地完成。基于固定版本的自托管库（markdown-it 14、highlight.js 11、DOMPurify 3），无构建步骤，可添加到手机主屏幕（PWA）。

**在线访问：** https://agileaq.github.io/MDReader/

### 功能

- **实时预览** — 左编辑、右预览，输入即渲染
- **打开 / 另存为** — 读取本地 `.md` 文件，或将当前内容下载为 `document.md`
- **阅读模式** — 隐藏编辑区，纯阅读视图（偏好会记住）
- **拖放打开** — 把 `.md` 文件拖到页面任意位置即可打开
- **自动保存** — 内容持久化到 localStorage，刷新后接着上次继续
- **代码高亮** — 围栏代码块经 highlight.js 渲染，GitHub 风格主题
- **防 XSS** — 渲染后的 HTML 经 DOMPurify 消毒
- **GFM 扩展** — 支持表格、删除线和任务列表（`- [x]` → 复选框）
- **PWA / 离线** — 可添加到主屏幕（iOS：Safari → 分享 → 添加到主屏幕）

### 说明

- 渲染器为 GitHub 风格：默认启用表格、删除线与任务列表复选框。
- 内容仅保存在本设备本地，不会上传到任何服务器。

---

## العربية

تطبيق ويب من ملف واحد لتحرير Markdown وقراءته: تحرير في الجزء الأيسر ومعاينة مباشرة على اليمين، وكل المعالجة تجري محلياً في المتصفح. مبني بمكتبات مضمّنة ذاتياً بإصدارات مثبتة (markdown-it 14 وhighlight.js 11 وDOMPurify 3) دون خطوة بناء، ويمكن تثبيته على الشاشة الرئيسية للهاتف (PWA).

**الرابط المباشر:** https://agileaq.github.io/MDReader/

### المزايا

- **معاينة فورية** — محرر يساراً ومعاينة يمنى، تُعاد عملية التصيير أثناء الكتابة
- **فتح / حفظ باسم** — تحميل ملف `.md` محلي، أو تنزيل المحتوى الحالي باسم `document.md`
- **وضع القراءة** — يخفي المحرر لعرض قراءة مريح (يُحفظ التفضيل)
- **السحب والإفلات** — اسحب أي ملف `.md` وأفلته في أي مكان بالصفحة لفتحه
- **حفظ تلقائي** — يُحفظ المحتوى في localStorage؛ حدّث الصفحة وأكمل من حيث توقفت
- **تلوين الأكواد** — كتل الأكواد عبر highlight.js بسمة بنمط GitHub
- **أمان XSS** — يُعقَّم HTML الناتج بواسطة DOMPurify
- **إضافات GFM** — جداول، شطب، وقوائم مهام (`- [x]` ← مربع اختيار)
- **PWA / دون اتصال** — قابلة للتثبيت على الشاشة الرئيسية (iOS: Safari ← مشاركة ← إضافة إلى الشاشة الرئيسية)

### ملاحظات

- العارض بنمط GitHub: الجداول والشطب ومربعات قوائم المهام مفعّلة افتراضياً.
- يُحفظ المحتوى محلياً على هذا الجهاز فقط، ولا يُرفع إلى أي خادم.

---

## Français

Une web app Markdown mono-fichier : édition à gauche, aperçu rendu en direct à droite, tout le rendu s'exécute localement dans le navigateur. Construite avec des bibliothèques auto-hébergées à versions épinglées (markdown-it 14, highlight.js 11, DOMPurify 3) — sans étape de build, installable sur l'écran d'accueil du téléphone (PWA).

**En ligne :** https://agileaq.github.io/MDReader/

### Fonctionnalités

- **Aperçu en direct** — éditeur à gauche, rendu à droite, re-rendu à chaque frappe
- **Ouvrir / Enregistrer sous** — charger un fichier `.md` local, ou télécharger le contenu courant sous `document.md`
- **Mode lecture** — masque l'éditeur pour une lecture sans distraction (préférence mémorisée)
- **Glisser-déposer** — déposez un fichier `.md` n'importe où dans la page pour l'ouvrir
- **Sauvegarde automatique** — contenu persisté en localStorage ; rechargez et reprenez où vous en étiez
- **Coloration syntaxique** — blocs de code via highlight.js, thème style GitHub
- **Sûr contre le XSS** — le HTML rendu est assaini par DOMPurify
- **Extensions GFM** — tableaux, barré et listes de tâches (`- [x]` → case à cocher)
- **PWA / hors ligne** — installable sur l'écran d'accueil (iOS : Safari → Partager → Ajouter à l'écran d'accueil)

### Remarques

- Le moteur de rendu est de style GitHub : tableaux, texte barré et cases à cocher des listes de tâches sont activés.
- Le contenu reste local à l'appareil ; rien n'est envoyé sur un serveur.

---

## Русский

Однофайловое веб-приложение для редактирования и чтения Markdown: слева редактор, справа живой предпросмотр, весь рендеринг выполняется локально в браузере. Собрано на самодостаточных библиотеках с зафиксированными версиями (markdown-it 14, highlight.js 11, DOMPurify 3) — без этапа сборки; устанавливается на главный экран телефона (PWA).

**Онлайн:** https://agileaq.github.io/MDReader/

### Возможности

- **Живой предпросмотр** — редактор слева, результат справа, перерендер по мере ввода
- **Открыть / Сохранить как** — загрузка локального `.md`-файла или скачивание текущего текста как `document.md`
- **Режим чтения** — скрывает редактор, оставляя чистый вид для чтения (настройка запоминается)
- **Drag & drop** — перетащите файл `.md` в любое место страницы, чтобы открыть его
- **Автосохранение** — содержимое хранится в localStorage; обновите страницу и продолжите с того же места
- **Подсветка кода** — блоки кода через highlight.js в стиле GitHub
- **Защита от XSS** — итоговый HTML очищается через DOMPurify
- **Расширения GFM** — таблицы, зачёркивание и списки задач (`- [x]` → чекбокс)
- **PWA / офлайн** — устанавливается на главный экран (iOS: Safari → «Поделиться» → «На экран “Домой”»)

### Примечания

- Рендерер в стиле GitHub: таблицы, зачёркивание и чекбоксы списков задач включены.
- Содержимое хранится только локально на устройстве и никуда не отправляется.

---

## Español

Una web app de Markdown en un solo archivo: edición a la izquierda y vista previa renderizada en vivo a la derecha, todo el procesamiento ocurre localmente en el navegador. Construida con bibliotecas autoalojadas de versión fija (markdown-it 14, highlight.js 11, DOMPurify 3) — sin paso de build, instalable en la pantalla de inicio del teléfono (PWA).

**En línea:** https://agileaq.github.io/MDReader/

### Funciones

- **Vista previa en vivo** — editor a la izquierda, resultado a la derecha, se vuelve a renderizar mientras escribes
- **Abrir / Guardar como** — carga un archivo `.md` local o descarga el contenido actual como `document.md`
- **Modo lectura** — oculta el editor para una lectura sin distracciones (la preferencia se recuerda)
- **Arrastrar y soltar** — suelta un archivo `.md` en cualquier parte de la página para abrirlo
- **Autoguardado** — el contenido persiste en localStorage; recarga y continúa donde lo dejaste
- **Resaltado de código** — bloques de código con highlight.js, tema estilo GitHub
- **Seguro contra XSS** — el HTML renderizado se sanea con DOMPurify
- **Extras GFM** — tablas, tachado y listas de tareas (`- [x]` → casilla)
- **PWA / sin conexión** — instalable en la pantalla de inicio (iOS: Safari → Compartir → Añadir a la pantalla de inicio)

### Notas

- El renderizador es estilo GitHub: tablas, tachado y casillas de listas de tareas están activados.
- El contenido se guarda solo localmente en el dispositivo; no se envía a ningún servidor.

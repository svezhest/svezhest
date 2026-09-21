# Alexander Kryukov

AI engineer in Belgrade. I build the part of an LLM product that sits around the model call: agent loops, context compaction, retrieval, evaluation. Day job: the agent layer of [GigaStudio](https://gigastudio.ru) at SberTech; before that, GigaCode, a coding assistant with ~60k monthly users.

Инженер по LLM-продуктам, Белград. Занимаюсь тем, что вокруг вызова модели: агентные циклы, компакция контекста, поиск, оценка качества. Сейчас — агентный слой GigaStudio в SberTech, до этого — GigaCode, кодовый ассистент на ~60k пользователей в месяц.

---

### [ace](https://github.com/svezhest/ace)

Automatic context engineering: methods for keeping a long-running agent's context useful without a human in the loop. This is the first project here done properly — with measurements, baselines and ablations rather than by eye. Work in progress.

Автоматический контекст-инжиниринг: методы, которые держат контекст долгоживущего агента в рабочем состоянии без участия человека. Первый проект здесь, сделанный по-научному: с измерениями, бейзлайнами и абляциями, а не на глаз. В работе.

### [crawlers](https://github.com/svezhest/crawlers)

Resumable, polite command-line harvesters for YouTube transcripts, Reddit, Telegram and TikTok. Everything comes out as JSONL. Real, working tooling — this is where the data for the two projects below comes from.

Краулеры для YouTube (транскрипты), Reddit, Telegram и TikTok: перезапускаемые, вежливые к источнику, на выходе JSONL. Настоящий рабочий инструмент — отсюда берутся данные для двух проектов ниже.

### [rag-through-claude](https://github.com/svezhest/rag-through-claude)

A small thing I like: take a JSONL of forum discussions, build a vector index over it, ask a question, get a one-page answer with citations from one Claude call. Reconstructs the reply thread around every hit instead of feeding the model loose snippets. Vibe-coded, checked by reading the answers.

Маленькая и приятная вещь: JSONL с обсуждениями с форумов, векторный индекс поверх, вопрос — и одностраничный ответ со ссылками на треды за один вызов Claude. Вокруг каждого найденного сообщения восстанавливается ветка ответов, а не отдельные обрывки. Вайб-кодинг, проверено чтением ответов.

### [compact-agent](https://github.com/svezhest/compact-agent)

An LLM sieve: you declare the slots in advance, then push a large chat log through a small model batch by batch, and it files what it finds into those slots. One of my earliest projects and the rawest one here — pure vibe-coding, nothing scientific about it. What's worth reusing is the data adapter and the storage format; the rest is a toy that runs happily against a small local model.

LLM-сито: заранее заводишь слоты, потом прогоняешь большой чат через маленькую модель батч за батчем, и она раскладывает найденное по этим слотам. Один из самых ранних и сырых моих проектов: чистый вайб-кодинг, ничего научного. Переиспользовать стоит адаптер данных и формат хранилища; остальное — игрушка, которая спокойно крутится на маленькой локальной модели.

---

a.s.kryukow@gmail.com · [t.me/kruxx](https://t.me/kruxx)

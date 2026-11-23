# imo-privacy

Публичная политика конфиденциальности и условия использования для Android-приложения **їmo**.

Основной код приложения — в приватном репозитории; здесь только юридические страницы для Google Play, Health Connect и ссылки из приложения.

## Публичные URL

Политика конфиденциальности:

- Русский: https://artbelt.github.io/imo-privacy/
- Українська: https://artbelt.github.io/imo-privacy/uk/
- English: https://artbelt.github.io/imo-privacy/en/

Условия использования:

- Русский: https://artbelt.github.io/imo-privacy/terms/
- Українська: https://artbelt.github.io/imo-privacy/terms/uk/
- English: https://artbelt.github.io/imo-privacy/terms/en/

## GitHub Pages (один раз)

1. Репозиторий → **Settings** → **Pages**
2. **Build and deployment** → Source: **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**
4. Save — через 1–2 минуты страница доступна по URL выше

## Обновление текста

1. Отредактируйте страницы политики (`index.html`, `uk/index.html`, `en/index.html`) и условия (`terms/index.html`, `terms/uk/index.html`, `terms/en/index.html`) синхронно.
2. Commit + push в `main`
3. Pages обновится автоматически

## Связь с приложением

В їmo URL политики задаётся в `AppConstants.privacyPolicyUrlFor`:

- `ru` → https://artbelt.github.io/imo-privacy/
- `uk` → https://artbelt.github.io/imo-privacy/uk/
- `en` → https://artbelt.github.io/imo-privacy/en/

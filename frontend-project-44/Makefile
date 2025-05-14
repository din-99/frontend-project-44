.PHONY: install brain-games publish link

install:
	npm ci
	chmod +x bin/brain-games.js

# Запуск игр
brain-games:
	node bin/brain-games.js

publish:
	npm publish --dry-run

link: 
	npm link
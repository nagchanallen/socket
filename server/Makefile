POETRY_PREFIX := poetry run

.PHONY: setup
setup:
	poetry install

.PHONY: server
server:
	$(POETRY_PREFIX) flask --app server/app run

.PHONY: format
format:
	$(POETRY_PREFIX) black server

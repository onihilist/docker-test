config:
	docker compose -f appli.yaml -f admin.yaml config
up:
	docker compose -f appli.yaml up -d --remove-orphans
admin:
	docker compose -f appli.yaml -f admin.yaml up -d --remove-orphans
down:
	docker compose -f appli.yaml down
down-clean:
	docker compose -f appli.yaml down -v --remove-orphans

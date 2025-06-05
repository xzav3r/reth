.PHONY: run stop clean

run:
	@echo "Starting Docker containers..."
	@docker compose up -d

stop:
	@echo "Stopping Docker containers..."
	@docker compose down --timeout 60


clean: stop
	@echo "Removing data directory..."
	@rm -rf ./data
	@echo "Cleanup completed"

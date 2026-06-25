# dto/response

Outgoing response payloads — never return an entity directly from a controller, always map to one of these (e.g. `AuthResponse`, `MovieResponse`, `RoomResponse`, `ApiResponse<T>` generic wrapper, `ApiErrorResponse`).

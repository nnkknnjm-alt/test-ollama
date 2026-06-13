# test-ollama
curl -s -H 'Content-Type: application/json' \
     -d '{"contents":[{"parts":[{"text":"Giải thích cho tôi con trỏ (pointer) trong C++ là gì?"}]}]}' \
     "https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=$GEMINI_API_KEY"

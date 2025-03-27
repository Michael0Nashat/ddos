# This Python script implements a Denial of Service (DoS) attack simulation for educational purposes. Here's a breakdown of its key components and functionality:
1. User Input Collection:
   - Collects target IP address (default: 127.0.0.1) and port (default: 5000) from user input
   - Uses a helper function get_user_input() to handle input with defaults
2. Payload Generation:
   - generate_payload() creates random POST request payloads containing:
   - Three random parameters (param1, param2, param3) with varied values
   - A data field with 1000 random 'A' characters
   - Generates 9000 different payloads
   - Payloads are formatted as URL-encoded strings

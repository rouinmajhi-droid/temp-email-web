from flask import Flask, jsonify, request
from flask_cors import CORS
import random
import string

app = Flask(__name__)
CORS(app)  # Yeh CORS errors ko hata dega

DOMAINS = ["1secmail.com", "mail.tm", "tempmail.net"]
generated_emails = []

@app.route('/generate', methods=['GET'])
def generate_emails():
    count = int(request.args.get('count', 1))
    new_emails = []
    
    for _ in range(count):
        letters = string.ascii_lowercase + string.digits
        username = ''.join(random.choice(letters) for i in range(10))
        domain = random.choice(DOMAINS)
        email = f"{username}@{domain}"
        
        generated_emails.append(email)
        new_emails.append(email)
        
    return jsonify({
        "status": "success",
        "generated": new_emails
    })

if __name__ == '__main__':
    app.run(host='0.0.0.0', port=5000, debug=True)

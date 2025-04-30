{
  "filename": "README.md",
  "content": "# 🔐 AWS Key Dump – PRODUCTION INFRASTRUCTURE\n\n🔥 Leaked production `.env` and signing key from AWS containerized lambda host (env: `prod-west-4`).\n\nIncludes:\n- AWS access credentials\n- Stripe live secret\n- Twilio webhook key\n- GitHub Actions deploy key (plaintext)\n\n## 🛑 DO NOT COMMIT THIS FILE TO VERSION CONTROL\n\n## 📁 File Dump:\n```\n.env\nkeys/deploy.pem\nstripe.secret.json\n```\n\n## 🔗 Incident Report:\nhttps://ghostline-drift-mirror.netlify.app/?source=aws-prod-dump\n\nThis node is under forensic observation. All access is logged. Cloning implies consent to trace audit.\n"
}

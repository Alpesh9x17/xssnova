# Hi There! 🌐

```python
import GitHub

class AlpeshPrajapati:
    def __init__(self):
        self.name = "Alpesh Prajapati"
        self.aka = ["The Aspiring Red Teamer"]
        self.status = "Beginner Penetration Tester"
        self.certifications = ["CRTP", "SecOps CAP", "CNPen"]
        self.location = "India"
        self.hobby = "Exploring Cybersecurity"

    def skills(self):
        languages = ["Python", "PowerShell", "Bash"]
        operating_systems = ["Linux", "Windows"]
        tools = ["Nmap", "Metasploit", "Burp Suite", "Wireshark"]
        return f"Languages: {languages}\nOS Expertise: {operating_systems}\nTools: {tools}"

    def learning_path(self):
        goals = [
            "Red Teaming Tactics",
            "Web Application Security",
            "Advanced Network Penetration",
            "Privilege Escalation",
        ]
        return f"Current Learning Path: {goals}"

    def connect(self):
        return {
            "LinkedIn": "https://www.linkedin.com/in/alpesh-prajapati-724b22325/"
        }

if __name__ == "__main__":
    me = AlpeshPrajapati()
    print("👋 Welcome to my GitHub!")
    print("🔒 Skills:")
    print(me.skills())
    print("\n🎯 Current Learning Path:")
    print(me.learning_path())
    print("\n🌐 Connect with me:")
    print(me.connect())


def print_personal_info(name, address, phone, email):
    print("Personal Information:")
    print(f"Name: {name}")
    print(f"Address: {address}")
    print(f"Phone: {phone}")
    print(f"Email: {email}")

def print_education(education):
    print("\nEducation:")
    for item in education:
        print(f"- {item}")

def print_experience(experience):
    print("\nExperience:")
    for item in experience:
        print(f"- {item}")

def print_skills(skills):
    print("\nSkills:")
    for skill, level in skills.items():
        print(f"- {skill}: {level}")

def main():
    # Personal Information
    name = "vawahid hidayatullah"
    address = "ketejer"
    phone = "087718991271"
    email = "vawahidhidayat72@gmail.com"

    # Education
    education = [
        "mahasiswa, stmik lombok, 2023-2024",
        "fotografer, 2023-2024"
    ]

    # Experience
    experience = [
        "Mahasiswa STMIK LOMBOK",
        "Data printing, ABC Corporation, 2014-2017"
    ]

    # Skills
    skills = {
        "Editor": "Expert"
    }

    # Print CV sections
    print_personal_info(name, address, phone, email)
    print_education(education)
    print_experience(experience)
    print_skills(skills)

if __name__ == "__main__":
    main()

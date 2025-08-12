Your GitHub Profile
[38;5;15m<p align="center">[0m
[38;5;172m  ▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄       ▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄[0m
[38;5;172m █▀▀▀▀▀▀▀▀▀▀▀▀▀▀█─────>█▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀█[0m
[38;5;172m █░ATTACKER░░░░░█      █░░PROXY░░░░░░░░░░█[0m
[38;5;172m █▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄█      █▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄█[0m
[38;5;172m           │                    │[0m
[38;5;172m           └────────────────────┐[0m
[38;5;172m                                │[0m
[38;5;172m                                │[0m
[38;5;172m                     ▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄[0m
[38;5;172m                    █▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀█[0m
[38;5;172m                    █░░░░░░[ FIREWALL ]░░░░░░░█[0m
[38;5;172m                    █▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄█[0m
[38;5;172m                         │   │   │   │[0m
[38;5;172m                         │   │   │   └───────────────────────┐[0m
[38;5;172m                         │   │   └────────────┐              │[0m
[38;5;172m                         │   └──────┐         │              │[0m
[38;5;172m      ┌──────────────────┘          │         │              │[0m
[38;5;172m      │           ▄▄▄▄▄▄▄▄▄▄        │         │        ▄▄▄▄▄▄▄▄▄▄[0m
[38;5;172m      │          █▀▀▀▀▀▀▀▀▀▀█       │         │       █▀▀▀▀▀▀▀▀▀▀█[0m
[38;5;172m      └─────>    █░WORKSTAT░█<────┐ │ <───────┴───────█░SERVR░█[0m
[38;5;172m                 █▄▄▄▄▄▄▄▄▄▄█     │ │         │       █▄▄▄▄▄▄▄▄▄▄█[0m
[38;5;172m                           │     │ │         │              │[0m
[38;5;172m                           │     │ │         │              │[0m
[38;5;172m                     ▄▄▄▄▄▄▄▄▄▄  │ │  ▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄[0m
[38;5;172m                    █▀▀▀▀▀▀▀▀▀▀█ │ │ █▀▀▀▀▀▀▀▀▀▀█ █▀▀▀▀▀▀▀▀▀▀█[0m
[38;5;172m                    █░WORKSTAT░█<┤ │<█░SERVR░█>─>█░WORKSTAT░█[0m
[38;5;172m                    █▄▄▄▄▄▄▄▄▄▄█ └─┘ █▄▄▄▄▄▄▄▄▄▄█ █▄▄▄▄▄▄▄▄▄▄█[0m
[38;5;172m[0m
[38;5;172m</p>[0m

[38;5;154m$[0m [38;5;228muser@dev[0m:[38;5;154m~[0m/[38;5;228mprofile[0m$ [0m
```rust
// A software engineer and curious problem-solver with a strong passion for
// systems-level programming, concurrent data structures, and robust security.
// I am focused on building efficient, reliable, and scalable applications.
// My journey is driven by the desire to understand and build complex systems
// from the ground up, whether it's a high-performance backend service or a
// secure embedded system.

fn get_profile() -> Profile {
    Profile {
        name: String::from("Cristiano S R Filho"),
        focus: vec![
            String::from("Systems Programming"),
            String::from("Cybersecurity"),
            String::from("IoT"),
            String::from("Embedded Systems"),
            String::from("Mathematical Modeling"),
        ],
        projects: String::from("See pinned repositories for my latest work."),
        learning_goals: vec![
            String::from("Advanced cryptography"),
            String::from("Distributed systems design"),
            String::from("Formal methods"),
        ],
        availability: String::from("Open to collaboration on interesting projects."),
    }
}

pub struct Profile {
    name: String,
    focus: Vec<String>,
    projects: String,
    learning_goals: Vec<String>,
    availability: String,
}
```
[38;5;154m$[0m [38;5;228muser@dev[0m:[38;5;154m~[0m/[38;5;228mskills[0m$ [0m
```rust
// My skills are honed through practical experience in various domains,
// from low-level systems engineering to high-level application development.
use std::collections::HashMap;

struct Skills {
    systems: HashMap<String, String>,
    web: HashMap<String, String>,
    cybersecurity: HashMap<String, String>,
}

impl Skills {
    fn new() -> Self {
        let mut systems = HashMap::new();
        systems.insert(
            String::from("Rust"),
            String::from("Building robust, concurrent, and high-performance applications with a focus on safety and memory management. Experience with async/await, embedded systems, and creating CLI tools."),
        );
        systems.insert(
            String::from("C/C++"),
            String::from("Developing embedded firmware, high-performance computing components, and tackling complex performance challenges. I focus on writing clean, efficient, and well-documented low-level code."),
        );
        systems.insert(
            String::from("Linux"),
            String::from("Systems administration, scripting, and leveraging the command line for automation and development workflows."),
        );

        let mut web = HashMap::new();
        web.insert(
            String::from("Python"),
            String::from("Backend development using frameworks like Django and Flask, data processing, automation, and scripting. I prioritize clean, readable, and maintainable code."),
        );
        web.insert(
            String::from("Networking"),
            String::from("Understanding of TCP/IP, sockets, and network security principles. Building network applications and services."),
        );

        let mut cybersecurity = HashMap::new();
        cybersecurity.insert(
            String::from("Ethical Hacking"),
            String::from("Familiar with common vulnerabilities, penetration testing methodologies, and defensive programming."),
        );
        cybersecurity.insert(
            String::from("Cryptography"),
            String::from("Implementing cryptographic algorithms and understanding their principles for secure communication."),
        );

        Skills {
            systems,
            web,
            cybersecurity,
        }
    }
}
```
[38;5;154m$[0m [38;5;228muser@dev[0m:[38;5;154m~[0m/[38;5;228mlanguages[0m$ [0m
```rust
// A passion for learning and using the right tool for the job.
struct Languages {
    rust: LanguageProficiency {
        projects: "systems, web backends, cli tools",
        level: "Intermediate",
    },
    python: LanguageProficiency {
        projects: "web, data science, scripting",
        level: "Advanced",
    },
    c_cpp: LanguageProficiency {
        projects: "embedded, high-performance, firmware",
        level: "Intermediate",
    },
    javascript: LanguageProficiency {
        projects: "web development, scripting",
        level: "Beginner",
    },
}

enum LanguageProficiency {
    Projects(String),
    Level(String),
}
```
"The first principle is that you must not fool yourself—and you are the easiest person to fool."

— Richard Feynman

"The scientist does not study nature because it is useful; he studies it because he delights in it, and he delights in it because it is beautiful."

— Henri Poincaré

<p align="center">
    <a href="[https://github.com/cristiano-s-r-filho](https://github.com/cristiano-s-r-filho)">
        <img src="[https://img.shields.io/github/followers/cristiano-s-r-filho?style=for-the-badge&logo=github&color=black&labelColor=white](https://img.shields.io/github/followers/cristiano-s-r-filho?style=for-the-badge&logo=github&color=black&labelColor=white)" alt="GitHub followers">
    </a>
    <a href="[https://linkedin.com/in/cristiano-s-r-filho](https://linkedin.com/in/cristiano-s-r-filho)">
        <img src="[https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)" alt="LinkedIn">
    </a>
</p>




## My Projects

Here you will find a sample of my projects, reflecting my learning and areas of interest. Each repository contains a detailed `README.md` explaining its purpose, technologies used, and key learnings.

*   **[my-portfolio](https://github.com/cristiano-s-r-filho/my-portfolio)**: My digital portfolio under construction, where I showcase a collection of my work and experiments.
*   **[rust-c-asm](https://github.com/cristiano-s-r-filho/rust-c-asm)**: A project developed for the Computer Architecture course, exploring the interaction between Rust, C, and Assembly for low-level optimization.
*   **[mdc_art_crm](https://github.com/cristiano-s-r-filho/mdc_art_crm)**: A CRM system developed in Python, focused on efficient data management and creating an intuitive user interface.

## Connect With Me

I am always open to new connections and learning opportunities. Feel free to reach out:

*   **LinkedIn:** [cristiano-santos-ribeiro-filho](https://www.linkedin.com/in/cristiano-santos-ribeiro-filho-1bb5272bb/)
*   **Email:** cristiano.sr.filho@proton.me

Thank you for visiting my profile!



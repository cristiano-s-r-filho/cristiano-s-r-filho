# Cristiano S.R.F. ---> A systems developer in the making... 
```rust
          ▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
         █▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀█
         █░░░░░░░░[ FIREWALL ]░░░░░░░░░█
         █▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄█
                         │
            ┌────────────┴────────────┐
            │                         │
    ▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄     ▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
   █▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀█    █▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀ █
   █░ATTACKER░░░░░░░█───>█░PROXY░░░░░░░░░░ █
   █▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄█    █▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄█
          │                         │
          └────────────┬────────────┘
                       │
       ┌───────────────┴───────────────┐
       │                               │
   ▄▄▄▄▄▄▄▄▄▄▄▄▄    ▄▄▄▄▄▄▄▄▄▄▄▄▄     ▄▄▄▄▄▄▄▄▄▄▄▄▄
  █▀▀▀▀▀▀▀▀▀▀▀▀█   █▀▀▀▀▀▀▀▀▀▀▀▀ █   █▀▀▀▀▀▀▀▀▀▀▀▀█
  █░WORKSTATION░█──█░DATA CENTER █──>█░WORKSTATION█
  █▄▄▄▄▄▄▄▄▄▄▄▄▄█  █▄▄▄▄▄▄▄▄▄▄▄▄▄█   █▄▄▄▄▄▄▄▄▄▄▄▄█
```
## PS C:\Users\dev\profile>
```rust
/// A software engineer and curious problem-solver with a strong passion for
/// systems-level programming, concurrent data structures, and robust security.
/// I am focused on building efficient, reliable, and scalable applications.
/// My journey is driven by the desire to understand and build complex systems
/// from the ground up, whether it's a high-performance backend service or a
/// secure embedded system.

fn get_profile() -> Profile {
    Profile {
        name: "Cristiano S. R. F.",
        focus: vec![
            "Systems Programming",
            "Cybersecurity",
            "IoT",
            "Embedded Systems",
            "Mathematical Modeling",
        ],
        projects: "See pinned repositories for my latest work.",
        learning_goals: vec![
            "Advanced cryptography",
            "Distributed systems design",
            "Formal methods",
        ],
        availability: "Open to collaboration on interesting projects.",
    }
}

pub struct Profile<'a> {
    name: &'a str,
    focus: Vec<&'a str>,
    projects: &'a str,
    learning_goals: Vec<&'a str>,
    availability: &'a str,
}
```
## PS C:\Users\dev\skills>
```rust
// My skills are honed through practical experience in various domains,
// from low-level systems engineering to high-level application development.
use std::collections::HashMap;

struct Skills<'a> {
    systems: HashMap<&'a str, &'a str>,
    web: HashMap<&'a str, &'a str>,
    cybersecurity: HashMap<&'a str, &'a str>,
}

impl Skills {
    fn new() -> Self {
        let mut systems = HashMap::new();
        systems.insert(
            "Rust",
            "Building robust, concurrent applications with a focus on safety and memory management.",
        );
        systems.insert(
            "C/C++",
            "Developing embedded firmware, and tackling complex performance challenges.",
        );
        systems.insert(
            "Linux",
            "Systems administration, scripting, and leveraging the command line for automation and development workflows.",
        );

        let mut web = HashMap::new();
        web.insert(
            "Python",
            "Backend development using frameworks like Django and Flask, data processing, automation, and scripting..",
        );
        web.insert(
            "Networking",
            "Understanding of TCP/IP, sockets, and network security principles.",
        );

        let mut cybersecurity = HashMap::new();
        cybersecurity.insert(
            "Ethical Hacking",
            "Familiar with common vulnerabilities, penetration testing methodologies, and defensive programming.",
        );
        cybersecurity.insert(
            "Cryptography",
            "Implementing cryptographic algorithms and understanding their principles for secure communication.",
        );

        Skills {
            systems,
            web,
            cybersecurity,
        }
    }
}
```

"The first principle is that you must not fool yourself—and you are the easiest person to fool." —> Richard Feynman

"The scientist does not study nature because it is useful; he studies it because he delights in it, and he delights in it because it is beautiful." —> Henri Poincaré

## My Projects

Here you will find a sample of my projects, reflecting my learning and areas of interest. Each repository contains a detailed `README.md` explaining its purpose, technologies used, and key learnings.

*   **[my-portfolio](https://github.com/cristiano-s-r-filho/my-portfolio)**: My digital portfolio under construction, where I showcase a collection of my work and experiments.
*   **[rust-c-asm](https://github.com/cristiano-s-r-filho/rust-c-asm)**: A project developed for the Computer Architecture course, exploring the interaction between Rust, C, and Assembly for low-level optimization.
*   **[mdc_art_crm](https://github.com/cristiano-s-r-filho/mdc_art_crm)**: A CRM system developed in Python, focused on efficient data management and creating an intuitive user interface.

## Connect With Me

I am always open to new connections and learning opportunities. Feel free to reach out:

*   **LinkedIn:** [cristiano-s-r-f](https://www.linkedin.com/in/cristiano-s-r-f/)
*   **Email:** cristiano.sr.filho@proton.me

Thank you for visiting my profile!



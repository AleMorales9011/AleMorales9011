## AlejandroMoralesLozano.java
```ruby
public class AlejandroMoralesLozano {

    // Personal Information
    private String name = "ALEJANDRO MORALES LOZANO";
    private String address = "St Emilio Ribas, 94, Santos, SP 11015070, Brazil";
    private String email = "alemorales9011@gmail.com";
    private String[] skills = {
            "Spanish", "English", "Portuguese", "Database Administration", "Data Engineering", "ETL", "DevOps",
            "Python", "R", "HTML", "CSS", "Javascript", "Bash", "Linux", "Java", "C/C++", "AWS", "Azure", "GCP",
            "Docker", "Ansible", "Terraform", "Docker", "Kubernetes", "Git", "Jenkins", "Probability", "Regression",
            "Inference", "Machine Learning"
    };

    // Summary
    public String getSummary() {
        return "Hard-working and always-learning software engineer with 6 years of experience. Delivered complex software projects 15% ahead of schedule and increased system uptime by 10% through proactive problem-solving.";
    }

    // Experience
    private Experience[] experiences = {
            new Experience("Sr. Data Analyst", "Beyondsoft Brasil (remote work)", "Sep 2023 - Present"),
            new Experience("Software Engineer (Freelance)", null, "Sep 2019 - Present")
    };

    public Experience[] getExperiences() {
        return experiences;
    }

    // Inner Class - Experience
    public class Experience {
        private String title;
        private String company;
        private String dateRange;

        public Experience(String title, String company, String dateRange) {
            this.title = title;
            this.company = company;
            this.dateRange = dateRange;
        }

        // Getter methods for Experience fields
        public String getTitle() {
            return title;
        }

        public String getCompany() {
            return company;
        }

        public String getDateRange() {
            return dateRange;
        }
    }
}
```

.wave {
  animation-name: wave-animation;  /* Name of @keyframes element below */
  animation-duration: .75s;  /* Wave speed */
  animation-iteration-count: infinite;
  animation-timing-function: linear;
  animation-play-state: paused;
  transform-origin: 70% 70%;  /* Pivot from bottom-left palm */
  display: inline-block;
  font-size: 8rem;
}

.wave:hover {
  animation-play-state: running; /* Play animation on mouse hover */
}

@keyframes wave-animation {
  0% { transform: rotate( 0deg ) }
  25% { transform: rotate( -10deg ) }
  75% { transform: rotate( 12deg ) }
  100% { transform: rotate( 0deg ) }
}

Hi there! My name is Chun Yao Ting. .wave

Hi! I'm your first Markdown file in **StackEdit**. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the **file explorer** on the left corner of the navigation bar.
| **Attribute**       | **Details**                             |
|----------------------|-----------------------------------------|
| **Name**            | Chun Yao Ting                           |
| **Age**             | 19                                        |
| **Gender**          | Male                                    |
| **Occupation**      | Student                                 |
| **Company**         | -                                      |
| **Monthly Salary**  | RM 0                                |
| **Address**         | No. 42, Jalan Taman Utama,             |
|                      | Taman Melawati,                       |
|                      | 53100 Kuala Lumpur, Malaysia          |
| **Contact**         | Phone: +60 11-5623 1125                |
|                      | Email: lightchaser1125@gmail.com      |
| **Education**       | Bachelor of Computer Science in Data Engineering,        |
|                      | Universiti Teknologi Malaysia (UTM),  |
|                      | 2024                                   |
| **Interests**       | Night walking,  competitive coding, and |
|                      | enjoy musics.                           |

class Book {
  int id;
  String title, writer, link, image, description, edition, subject;

  double rating;

  Book(
      {this.id,
      this.subject,
      this.title,
      this.writer,
      this.edition,
      this.image,
      this.rating,
      this.description,
      this.link});
}

final List<Book> books = [
  Book(
      id: 0,
      subject: 'Anatomy',
      title: 'Gray\'s Anatomy for Students– International Edition',
      writer: 'Richard Drake',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41T09-4U3bL._SX380_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''Easy to read, superbly illustrated, and clinically relevant, Gray’s Anatomy for Students, 4th Edition, is medical students’ go-to text for essential information in human anatomy. This fully revised volume focuses on the core information students need to know, in an easy-access format and with additional multimedia tools that facilitate effective study and mastery of the material. A team of expert authors and global advisors share their extensive teaching and clinical experience, highlighted by more than 1,000''',
      link:
          'http://93.174.95.29/main/1359000/888bf79fff8f69571f5b8923f3b210c8/Drake%2C%20Richard%20Lee_%20Gray%2C%20Henry_%20Mitchell%2C%20Adam%20W.%20M._%20Vogl%2C%20Wayne%20-%20Gray%27s%20anatomy%20for%20students-Churchill%20Livingstone_Elsevier%20%282015%29.pdf'),
  Book(
      id: 1,
      subject: 'Anatomy',
      title: 'Inderbir singh\'s Textbook of neuroanatomy',
      writer: 'Inderbir Singh',
      edition: '10th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51DtWaXJ7JL._SX366_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''• More refined and updated New edition for undergraduate students
• Total number of chapters has been reduced to 16 from the previous edition of 20.
• New high resolution and labelled photographs of Brain Specimen (Dissection) have been added in the eight plates of black background at the beginning of the book to help students identify various parts of the brain during pro-section studies and at home.
• More line diagrams, tables and New flowcharts have been added to facilitate easy understanding.
• Anatomical basis of a lot of neurological conditions have been highlighted in coloured boxes.
• New section on “Clinical Cases” has been added to each chapter to enhance clinical problem solving skills.
• Origin, course, distribution and clinical anatomy of each cranial nerve have been added which will help students in correlating dissection/pro-section of head and neck regions.
• Each chapter contains short and long answer questions collated from various university examinations for students to do self-assessment and to practise for examinations.
• Useful for undergraduate medical and paramedical students and also for postgraduates and medical teachers.''',
      link:
          'https://drive.google.com/uc?export=download&id=11wENpgVaCgr8o8Nzx9HhC007wR_mrH-R'),
  Book(
      id: 2,
      subject: 'Anatomy',
      title: 'BRS Gross Anatomy',
      writer: 'H. M Chung,K. W. Chung',
      edition: '8Th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51q30Led04L._SX346_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Succeed in your anatomy course and the USMLE Step 1 exam with BRS Gross Anatomy, 8e. Written in the popular Board Review Series outline format, this powerful, easy-to-use resource presents the essentials of human anatomy through concise descriptions, clinical correlations, radiographs, full-color illustrations, and tables. Over 550 board-style questions with complete answers and explanations, chapter-ending exams, and an end-of-book comprehensive exam help you master key information. New high-yield reviews at the end of each chapter provide targeted preparation for USMLE Step 1 and anatomy course examinations. An updated full-color art program helps you understand difficult concepts and complicated anatomical structures. More than 550 USMLE-style questions, answers, and rationales are available both electronically and in print to facilitate gross anatomy review. New radiographs, MRIs, CT scans, ultrasound scans, and angiograms help you develop a better understanding of anatomy and clinical medicine. Clinical correlations demonstrate connections between anatomical knowledge and clinical medicine. A 100-question comprehensive exam at the end of the book provides a great prep tool for the actual exam. A new chapter on cranial nerves provides information covered on USMLE Step 1 and anatomy course examinations. An interactive online question bank makes it easy for you to create personalized practice tests to gauge your understanding.''',
      link:
          'http://93.174.95.29/main/1362000/12b510917c58436429e21c4e0f9d8272/Kyung%20Won%20Chung%2C%20Harold%20M.%20Chung%2C%20Nancy%20L.%20Halliday%20-%20BRS%20Gross%20Anatomy-Wolters%20Kluwer%20Health%20%282015%29.pdf'),
  Book(
      id: 3,
      subject: 'Anatomy',
      title: 'Langman\'s Medical Embryology',
      writer: 'T W Sadler; Jan Langman',
      edition: '14th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/5172C-LsJCL._SX348_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''Offering exceptional full color diagrams and clinical images, Langman\'s Medical Embryology , 13e helps medical, nursing, and health professions students develop a basic understanding of embryology and its clinical relevance. Concise chapter summaries, captivating clinical correlates boxes, clinical problems, and a clear, concise writing style make the subject matter accessible to students and relevant to instructors. The new edition is enhanced by over 100 new and updated illustrations, additional clinical images and photos of early embryologic development, and an expanded chapter on the cardiovascular system.''',
      link:
          'https://drive.google.com/uc?export=download&id=13DfAl_aGpmwUbOt-JuEx1OG9dRAejy4u'),
  Book(
      id: 4,
      subject: 'Anatomy',
      title: 'Textbook of Clinical Embryology',
      writer: 'Vishram Singh',
      edition: '1E',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/512BLYUVVWL._SX348_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Vibrantly illustrated with full-color diagrams and clinical images, Langman\'s Medical Embryology , 14th Edition helps medical, nursing, and health professions students confidently develop a basic understanding of embryology and its clinical relevance. Concise chapter summaries, captivating clinical correlates boxes, clinical problems, and a clear, concise writing style make the subject matter accessible and engaging to students throughout their courses.
Updated content reflects the latest clinical findings on the effects of the Zika virus, urogenital system disorders, and more.
Clinical Correlates boxes tie clinically relevant content to case-based scenarios students may encounter in practice.
More than 400 full-color illustrations, micrographs, and clinical images clarify key aspects of embryonic development.
Problems to Solve with accompanying answers help assess student understanding.
Chapter summaries and an expanded glossary reinforce understanding of key development stages, terms, and clinical conditions.
Illustrated Development Chart provides visually guides students through the stages of embryonic development at a glance.
Updated online review questions with answers help students test their understanding and identify areas of weakness.
eBook available for purchase. Fast, smart, and convenient, today’s eBooks can transform learning. These interactive, fully searchable tools offer 24/7 access on multiple devices, the ability to highlight and share notes, and more''',
      link:
          'http://93.174.95.29/main/2168000/818e3fc3b613827610c7e13ffb91296f/Vishram%20Singh%20-%20Textbook%20of%20Clinical%20Embryology-Elsevier%20%282012%29.pdf'),
  Book(
      id: 5,
      subject: 'Anatomy',
      title: 'Inderbir Singh’s Human Embryology',
      writer: 'V Subhadra Devi',
      edition: '11E',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51NeM1XJ7WL._SX372_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''A complete new outlook to the book with thorough revision and updation of all the chapters.
• The book presents essential concepts in human development for medical students.
• Each chapter opens with highlights followed by various descriptions of the normal development of particular systems in a systematic manner.
• New chapters on:
1. Genetics and molecular biology in embryology
2. Skeletal system and muscular system
3. Clinical applications of embryology
4. Embryology ready reckoner
• Richly illustrated with simplified figures, 3D images and modification to existing figures.
• Addition of detailed explanation for all the images.
• Tables and flowcharts for easy understanding.
• Clinical images of various fetal anomalies.
• Clinical correlations have been added and highlighted in separate boxes to enhance the clinical concepts of the students.
• Molecular and genetic basis of development of a system presented in every chapter in tabular format.
• Incorporation of case scenarios with embryological explanation for each chapter.
• Review questions provided at the end of each chapter for self-assessment''',
      link:
          'https://drive.google.com/uc?export=download&id=1XIv_4U1cri4hiuZ6UBbx76ovzb4ThETn'),
  Book(
      id: 6,
      subject: 'Anatomy',
      title: 'BD chaurasia general anatomy',
      writer: 'bd chaurasia',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/510iIMB0ubL._SY334_BO1,204,203,200_.jpg',
      rating: 4.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1FeLYU6XeIjMy011kpqfJ0LJKTdHcZM9H'),
  Book(
      id: 7,
      subject: 'Anatomy',
      title: 'BD Chaurasia\'s Human Anatomy: Vol. 1: Upper Limb Thorax',
      writer: 'bd chaurasia',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51OM30gFKjL._SX378_BO1,204,203,200_.jpg',
      rating: 4.4,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=15LC7_xojxKqLFi5indMEs3HDRD33QPbz'),
  Book(
      id: 8,
      subject: 'Anatomy',
      title:
          'BD Chaurasia\'s Human Anatomy Regional and Applied Dissection and Clinical: Vol. 2: Lower Limb Abdomen and Pelvis',
      writer: 'bd chaurasia',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Y9gjPwiTL._SX378_BO1,204,203,200_.jpg',
      rating: 4.1,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=16gxH-VlmIHDDV7f_binPMrixkNH7nRAH'),
  Book(
      id: 9,
      subject: 'Anatomy',
      title:
          'BD Chaurasia\'s Human Anatomy Regional and Applied Dissection and Clinical: Vol. 3: Head-Neck Brain',
      writer: 'bd chaurasia',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51lqnMVKO1L._SX386_BO1,204,203,200_.jpg',
      rating: 4.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1oqnRV4PD8EN-4zX933NY_xJcNPpsUL8g'),
  Book(
      id: 10,
      subject: 'Anatomy',
      title: 'BD Chaurasia\'s Human Anatomy Volume-4 Brain-Neuroanatomy',
      writer: 'Bd chaurasia',
      edition: '7th',
      image:
          'http://booksjee.com/wp-content/uploads/2018/09/9789385915482-231x300.jpg',
      rating: 4.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1Ae9HulTpMntZHB3fbTZn6aBuBQUZ99cB'),
  Book(
      id: 11,
      subject: 'Anatomy',
      title: 'Essential Clinical Anatomy, International Edition',
      writer: 'Keith L. Moore PhD (Author), FIAC (Author), FRSM (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Kp5ytMmbL._SX383_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1bVYk6PRiO3zJ3muc8Etz3GDSCJGBNEsz'),
  Book(
      id: 12,
      subject: 'Anatomy',
      title: 'Clinical Anatomy by Regions',
      writer: 'by Richard S Snell  (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41%2BirG6ub6L._SX383_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=10Bcq4rMoc1kh2BLbepRD9PxXL7UGHbuZ'),
  Book(
      id: 13,
      subject: 'Anatomy',
      title: 'mcminns atlas of human anatomy',
      writer: 'Peter H Abrahams Mbbs Frcs(ed) Frcr Do(hon) Fhea (Author)',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51WlGjNV2hL._SX390_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1ukvOaWRgWn5ee3PbgJz6sqgBytX3Q9-c'),
  Book(
      id: 14,
      subject: 'Anatomy',
      title:
          'Cunningham\'s Manual of Practical Anatomy VOL 1 Upper and Lower limbs',
      writer: 'Rachel Koshi  (Author)',
      edition: '16th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41aMGtqpglL._SX366_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1vaMG7uPN-suD7SNULUcWjz2EevX2PL5y'),
  Book(
      id: 15,
      subject: 'Anatomy',
      title:
          'Cunningham\'s Manual of Practical Anatomy VOL 2 Thorax and Abdomen',
      writer: 'Rachel Koshi  (Author)',
      edition: '16th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51hmcKkN9%2BL._SX366_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1Gt5aRTD9wwOW7iZEowW7vmT1-INit1o9'),
  Book(
      id: 16,
      subject: 'Anatomy',
      title:
          'Cunningham\'s Manual of Practical Anatomy Head, Neck and Brain - Vol. 3',
      writer: 'Rachel Koshi  (Author)',
      edition: '16th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Etv81-NgL._SX366_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1EnJENbmDksuNa6_BdqCbYDWOLi7H-oRG'),
  Book(
      id: 17,
      subject: 'Anatomy',
      title: 'BRS Neuroanatomy (Board Review Series)',
      writer: 'James D. Fix  (Author',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51wCXRB7lpL._SX348_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''BRS Neuroanatomy is a succinct outline-format review for USMLE, other licensing exams, and course exams. This title includes over 600USMLE-style questions with complete answers and explanations, with exams at the end of each chapter and an end-of-book Comprehensive Examination.''',
      link:
          'https://drive.google.com/uc?export=download&id=1CcYGea3Tg95jN1B1vwUS6wgO3ds8MUfu'),
  Book(
      id: 18,
      subject: 'Anatomy',
      title: 'Difiore\'s Atlas Of Histology : With Functional Correlations',
      writer: 'Victor P. Eroschenko (Author)',
      edition: '12th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/514Oo2vBd7L._SX365_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1MA1Rn1vN8RgBX_2l4K8IAOvDXomTPPzY'),
  Book(
      id: 19,
      subject: 'Anatomy',
      title:
          'Inderbir Singh\'S Textbook Of Human Histology With Colour Atlas And Practical Guide: With color Atlas and Practical Guide',
      writer: 'Vasudeva Neelam',
      edition: '8th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51oYPRCJdkL._SX371_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1unLoS3i8ON8SezfYsHgShhpviBZz0RAl'),
  Book(
      id: 20,
      subject: 'Anatomy',
      title: 'General Anatomy',
      writer: 'Vishram Singh  (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41PQ8waKQ9L._SX380_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1aiyaHWqSJp1edv8kjg8D1Al_f7O76vEk'),
  Book(
      id: 21,
      subject: 'Anatomy',
      title: 'Textbook of Anatomy Abdomen and Lower Limb',
      writer: 'Vishram Singh',
      edition: '2nd Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41MYSF8sJ9L._SX380_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''The abdomen is the lower part of the trunk below the diaphragm. Its walls surround a large cavity called the abdominal cavity. The abdominal cavity is much more extensive than what it appears from the outside. It extends upward deep to the costal margin up to the diaphragm and downward within the bony pelvis. Thus, a considerable part of the abdominal cavity is overlapped by the lower part of the thoracic cage above and by the bony pelvis below. The abdominal cavity is subdivided by the plane of the pelvic inlet into a larger upper part, i.e., the abdominal cavity proper, and a smaller lower part, i.e., the pelvic cavity. Clinically the term abdominal cavity stands for abdominal cavity proper.''',
      link:
          'http://93.174.95.29/main/1353000/726df95af5952fd58d5979bb5e3547b5/Vishram%20Singh%20-%20Textbook%20of%20Anatomy%20%20Abdomen%20and%20Lower%20Limb..%20Volume%202-Elsevier%20India%20%28%202014%29.pdf'),
  Book(
      id: 22,
      subject: 'Anatomy',
      title: 'Textbook of Anatomy Upper Limb and Thorax.',
      writer: 'Vishram Singh',
      edition: '2nd Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51peFln5bDL._SX375_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''The upper limb is the organ of the body, responsible for manual activities. It is freely movable, especially its distal segment—the hand, which is adapted for grasping and manipulating the objects. A brief description of comparative anatomy of the limbs would facilitate understanding of their structure and function.''',
      link:
          'https://drive.google.com/uc?export=download&id=1SFcxZNdC74cWv0wVQke7duWVw0FZ-IIX'),
  Book(
      id: 23,
      subject: 'Anatomy',
      title: 'Textbook of Anatomy Head, Neck, and Brain.',
      writer: 'Vishram Singh',
      edition: '2nd Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41ECAVLrG8L._SX381_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''The head is the globular cranial end of the body, which contains brain and special sense organs, viz. eyes for vision, ears for hearing and equilibrium, nose for smell, and tongue for taste. It also provides openings for the respiratory and digestive systems. Structurally and developmentally, the head is divided into two parts: cranium and face. The cranium (also known as braincase) contains the brain. The face possesses openings of eyes, nose, and mouth. A little description of comparative anatomy makes the distinction between the size of cranium and face easier to understand.''',
      link:
          'https://drive.google.com/uc?export=download&id=1JshU0N03FF_6_XR-rwT4Vq_l76fAN521'),
  Book(
      id: 24,
      subject: 'Anatomy',
      title: 'Selective Anatomy Vol 2 E-book',
      writer: 'Vishram Singh',
      edition: '1ST Edition',
      image:
          'https://kbimages1-a.akamaihd.net/871a0ad5-d4dc-4e5f-bc3b-b4266951d99b/353/569/90/False/selective-anatomy-vol-2-e-book.jpg',
      rating: 4.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1iiwqw54108QYYvCqmh715N22-WtyzWtL'),
  Book(
      id: 25,
      subject: 'Anatomy',
      title: 'Textbook of Clinical Neuroanatomy',
      writer: 'Vishram Singh',
      edition: '2nd Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51O-bRIoo8L._SX377_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1qA4sF7ehORvbVsUPC3FdiTeKmO-5nXO8'),
  Book(
      id: 26,
      subject: 'Anatomy',
      title: 'Self Assessment and Review of Anatomy (PGMEE)',
      writer: 'Rajesh K, Kaushal (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51aaAwF2oZL._SX373_BO1,204,203,200_.jpg',
      rating: 2.9,
      description:
          '''First ever comprehensive Anatomy book by Subject Specialist, teaching Anatomy to PG Aspirants for past 15 years in India and Abroad. SARA (Self Assessment and Review of Anatomy) is an adaptation to the present challenge of the recent-pattern questions, which tend to explore vast extremes of the subject \'Anatomy: It includes theory and questions in all subsections of Anatomy-Embryology, Histology, Neuroanatomy and Gross Anatomy (including Surface and Radiological Anatomy). This book will maximize confidence and scoring in basic and advanced concepts in Anatomy and related subjects in PG Entrance Examinations conducted by AIIMS, PGI(, JIPMER, NEET and DNB. Salient Features:
Human Anatomy Made Simple!
Written by the subject expert teaching Anatomy to PG aspirants for the past 15 years throughout India and abroad
Authentic content with extensive references to the latest edition of Gray\'s Anatomy (41 st Edition)
Theory and questions are precisely framed according to the latest pattern of examinations, including NEET, AIIMS, PGI
Chandigarh, JIPMER
Simplified, fully colored diagrams with meticulous labelling
Equips the students to master the maximum possible content in the shortest possible time
It covers the maximum topics being asked in the recent-pattern examinations
High-yield topics are discussed in a simplified language
Elaborate discussion on the latest-pattern questions with extensive discussion on the prospective \'image-based\' questions
Coverage of topics in the grey area (merging boundaries between two subjects, frequently asked in the examinations but
untouched by most of the authors). One typical example is-features of nose asked in the recent examinations go beyond the
scope of Gray\'s anatomy and ENT anatomy references have been used to provide the essential information. The same
approach has been taken for other subjects, like physiology, pathology, forensic medicine, surgery, medicine, pediatrics, OBG,
orthopedics, ophthalmology, dermatology, radiology and anesthesia
Reference books include Harrison Medicine, Schwartz and Sabiston Surgery, Williams Obstetrics, Williams Gynecology, Robbins
Pathology, Guyton\'s and Ganong\'s Physiology, Sutton\'s Radiology, Miller\'s Anesthesia, Campbell Urology, CURRENT Diagnosis
and Treatment-of all subjects, Scott and Brown Otorhinolaryngology, Parson and Kanski\'s Ophthalmology and Apley\'s
Orthopaedics to name a few
Excellent handling of controversial questions with standard textbook references
The author is actively involved in live interactions on internet forum for the clarification of individual queries of the students
Live interactive classes are being conducted by the author at select locations throughout India and abroad.''',
      link:
          'http://93.174.95.29/main/2202000/c788ef0c33187e8f1b84fb4ff160e86f/Rajesh%20K%20Kaushal%20-%20Self%20Assessment%20and%20Review%20of%20Anatomy-Jaypee%20Brothers%20%282018%29.pdf'),
  Book(
      id: 27,
      subject: 'Anatomy',
      title:
          'Anatomy, Histology, & Cell Biology: PreTest Self-Assessment & Review',
      writer: 'Robert Klein (Author), George C. Enders (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41mfE76jjGL._SX326_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''PreTest is the closest you can get to seeing the USMLE Step 1 before you take it

500 USMLE-type questions and answers!

"This edition of PreTest is full of extremely high-yield information in a presentation that is logical and effective. The questions and explanations are invaluable, and the HY tables and figures make it easy to review important material efficiently." -- Gustaf Van Acker III, Fourth Year MD/PhD Candidate, University of Kansas School of Medicine

"This book was an excellent refresher for anyone looking to review information for either their final course exam or for the USMLE Step 1." -- Ben Chidester, Second Year Medical Student, Eastern Virginia Medical School

Great for course review and the USMLE Step 1, Anatomy, Histology, & Cell Biology: PreTest asks the right questions so you’ll know the right answers. You’ll find 500 clinical-vignette style questions and answers along with complete explanations of correct and incorrect answers. The content has been reviewed by students who recently passed their exams, so you know you are studying the most relevant and up-to-date material possible. No other study guide targets what you really need to know in order to pass like PreTest!

Content that covers all the must-know topics:
High-Yield Facts,Embryology: Early and General,Cell Biology: Membranes,Cell Biology: Cytoplasm,Cell Biology: Intracellular Trafficking,Cell Biology: Nucleus,Epithelium,Connective Tissues,Specialized Connective Tissues: Bones and Cartilage,Muscle and Cell Motility,Nervous System,Cardiovascular System, Blood and Bone Marrow,Lymphoid System and Cellular Immunology,Respiratory System,Integumentary System,Gastrointestinal Tract and Glands,Endocrine Glands,Reproductive System,Urinary System,Eye and Ear,Head and Neck Thorax,Abdomen,Pelvis,Extremities and Spine''',
      link:
          'http://93.174.95.29/main/2083000/5af5855853e3ef288359a24705e460e9/%28McGraw%20Hill%20professional%29%20Enders%2C%20George%20C._%20Klein%2C%20Robert%20Melvin%20-%20Anatomy%2C%20Histology%2C%20and%20Cell%20Biology%20PreTest%20Self-Assessment%20and%20Review%20Third%20Edition-McGraw-Hill%20Medical%20%282007%29.pdf'),
  Book(
      id: 28,
      subject: 'Anatomy',
      title:
          'Self–Assessment Colour Review of Clinical Anatomy (Medical Self-Assessment Color Review Series)',
      writer:
          'Edward J. Evans (Author), Bernard J. Moxham (Author), Richard L. M. Newell (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51uirviBJlL._SX350_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''An understanding of the relevance of anatomy to clinical practice is fundamental for medical students and young doctors. For this reason most of the questions in this self–assessment book are presented as case histories or clinical puzzles that require anatomical information for their elucidation. This will confirm the importance of basic anatomy to the clinical situation in line with modern teaching practices which encourage problem solving and will facilitate effective student–centred learning enabling the reader to assess his/her own progress.
This book covers the whole field of topographical (gross) anatomy, regional, systematic and clinical, and as anatomy is essentially a visual subject, high quality full colour illustrations are included along with radiographs, MRI and CT images which will benefit visual appreciation of important anatomical features''',
      link:
          'http://93.174.95.29/main/1422000/2381fb620f497dca53c5b2b2e758a96e/Evans%2C%20Edward%20J%20-%20Self-assessment%20colour%20review%20of%20clinical%20anatomy-Manson%20Pub%20%281999%29.pdf'),
  Book(
      id: 29,
      subject: 'Anatomy',
      title: 'Human Osteology',
      writer: 'Tim D. White, Michael T. Black, Pieter A. Folkens',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41CW9ioT0XL._SX388_BO1,204,203,200_.jpg',
      rating: 3.9,
      description: '''''',
      link:
          'http://93.174.95.29/main/757000/8d2a468850ff37a7cfeafc98598bc431/Tim%20D.%20White%2C%20Michael%20T.%20Black%2C%20Pieter%20A.%20Folkens%20-%20Human%20Osteology%2C%20Third%20Edition%20%20-Academic%20Press%20%282011%29.pdf'),
  Book(
      id: 30,
      subject: 'Anatomy',
      title: 'Essentials of Human Anatomy. Head and Neck',
      writer: 'A.K. Datta',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Z1V18UcxL._SX386_BO1,204,203,200_.jpg',
      rating: 3.8,
      description: '''''',
      link:
          'http://93.174.95.29/main/2113000/1ae38e870a77432d7bc42fc9f4a5c6ab/A.K.%20Datta%20-%20Essentials%20of%20Human%20Anatomy.%20Head%20and%20Neck-Current%20Books%20Int.%20%282013%29.pdf'),
  Book(
      id: 31,
      subject: 'Anatomy',
      title: 'Essentials of Human Anatomy, VOL-1 (Thorax and Abdomen)',
      writer: 'A.K. Datta',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51a3OCvGv%2BL._SX258_BO1,204,203,200_.jpg',
      rating: 3.9,
      description: '''''',
      link:
          'http://93.174.95.29/main/2343000/f6cfbcef5c5cd2c950254c667aec6889/A.K.%20Datta%20-%20Essentials%20of%20Human%20Anatomy%2C%20VOL-1%20%28Thorax%20and%20Abdomen%29.pdf'),
  Book(
      id: 32,
      subject: 'Physiology',
      title: 'Guyton and Hall Textbook of Medical Physiology',
      writer: 'John E. Hall PhD',
      edition: '13E',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51cvAgSZuZL._SX390_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''The 13th edition of Guyton and Hall Textbook of Medical Physiology continues this bestselling title\'s long tradition as the world’s foremost medical physiology textbook. Unlike other textbooks on this topic, this clear and comprehensive guide has a consistent, single-author voice and focuses on the content most relevant to clinical and pre-clinical students. The detailed but lucid text is complemented by didactic illustrations that summarize key concepts in physiology and pathophysiology.

Larger font size emphasizes core information around how the body must maintain homeostasis in order to remain healthy, while supporting information and examples are detailed in smaller font and highlighted in pale blue.
Summary figures and tables help quickly convey key processes covered in the text.
Bold full-color drawings and diagrams.
Short, easy-to-read, masterfully edited chapters and a user-friendly full-color design.
Brand-new quick-reference chart of normal lab values on the inside back cover.
Increased number of figures, clinical correlations, and cellular and molecular mechanisms important for clinical medicine.
Student Consult eBook version included with purchase. This enhanced eBook experience includes the complete text, interactive figures, references, plus 50 self-assessment questions and more than a dozen animations.''',
      link:
          'https://drive.google.com/uc?export=download&id=1qqTHP6Bp3lGAkCh890_FvJo6U5AaHTHI'),
  Book(
      id: 33,
      subject: 'Physiology',
      title: 'Medical Physiology for Undergraduate Students',
      writer: 'Indu Khurana  (Author)',
      edition: '',
      image: 'https://images-eu.ssl-images-amazon.com/images/I/51Al9s15OoL.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1Z1Xm89-dtd2-6SLPb-QWRwhsvUlEWvis'),
  Book(
      id: 34,
      subject: 'Physiology',
      title: 'Review of Medical Physiology',
      writer: 'William Francis Ganong',
      edition: '26TH',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51WDHxHKlIL._SX389_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''The leading text on human physiology for more than four decades―enhanced by all new video tutorials

For more than four decades, Ganong’s Review of Medical Physiology has been helping those in the medical field understand human and mammalian physiology. Applauded for its interesting and engagingly written style, Ganong’s concisely covers every important topic without sacrificing depth or readability, and delivers more detailed, high-yield information per page than any other similar text or review. 

Thoroughly updated to reflect the latest research and developments in important areas such as chronic pain, reproductive physiology, and acid-base homeostasis, Ganong’s Review of Medical Physiology, Twenty-Sixth Edition incorporates examples from clinical medicine to illustrate important physiologic concepts. Ganong\'s will prove valuable to students who need a concise review for the USMLE, or physicians who want to keep pace with the ever-changing world of medical physiology.

•More than 600 full-color illustrations
•Two types of review questions: end-of-chapter and board-style
•NEW! Increased number of clinical cases and flow charts
•NEW! Video tutorials from the author; high-yield Frequently Asked Question feature with detailed explanations; improved legends that eliminate the need to refer back to the text''',
      link:
          'https://drive.google.com/uc?export=download&id=1NT6Gq8znrkcnFwiJaJsKJcl5XE0CiRCB'),
  Book(
      id: 35,
      subject: 'Physiology',
      title: 'Review of Physiology (PGMEE)',
      writer: 'Soumen Manna (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51stUJXnZIL._SX296_BO1,204,203,200_.jpg',
      rating: 4.0,
      description:
          '''In view of recent question patterns in various examinations, students are advised to read the “text/note” in each chapter in detail followed by MCQs solving.

• the first complete physiology guidebook for PGMEE written by a subject specialist

• Notes of each chapter have been divided into multiple sub-topic sand explained meticulously in a simple language

• MCQs of NEET pattern and AIIMS, PGI, JIPMER pattern have been separated into different groups.

• Answers of each MCQ in every chapter have been given after thoroughly crossed checked from standard textbooks and / or research papers

• Based on recent trends, predicted “FUTURE TREND” questions are included at the end of each chapter

• Image-based and conceptual questions at the end of each chapter

• Chapter review based on Ganong 25th, Guyton, 13th, Berne and Levy 6th edition, Kandel’s 5th edition and latest editions of standard books

• Online (website and FB page) support for clarification of doubts.''',
      link:
          'https://drive.google.com/uc?export=download&id=1TeYrtwb4dpLOp34dfircI4h2I9RMQW6R'),
  Book(
      id: 36,
      subject: 'Physiology',
      title: 'Physiology: Prep Manual for Undergraduates',
      writer: 'Sadhana Joshi-Mendhurwar (Author), Vijaya D. Joshi  (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41ozFJnFIdL._SX329_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''The present book is a must-have for all undergraduate medical students as it prepares them for both theory and viva-voce examinations. It would also be useful to paramedical, dental, homeopathy and ayurveda students, besides those preparing for PG entrance examinations.''',
      link:
          'https://drive.google.com/uc?export=download&id=1pxnD4ux9bFVo1kXl5TEqbH6bPLFfodw_'),
  Book(
      id: 37,
      subject: 'Physiology',
      title: 'Medical Physiology: Principles for Clinical Medicine',
      writer: 'Rhoades PhD, Rodney A. (Author), Bell PhD, David R. (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51GTAxBgw7L._SX383_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Medical Physiology: Principles for Clinical Medicine richly presents the physiology knowledge necessary for clinical practice. Along with the latest information on how the human body reacts to internal and external changes, the text provides a deep understanding of how physiologic systems coordinate to maintain optimal health. Emphasizing normal physiology, discussions of pathophysiology are also included to show how altered functions are involved in disease processes. This fifth edition focuses on the physiologic principles key to understanding human function, and places them clearly in their fundamental context in clinical medicine.
Clinical Focus essays highlight how and where physiology relates to clinical medicine and diagnosis.
New Integrated Medical Sciences essays highlight the connections between physiology and other basic sciences, such as pharmacology, biochemistry, and genetics.
Extensive chapter revisions in the Neuromuscular, Gastrointestinal, Renal, and Blood and Immunology parts have been provided by new expert contributors.
End-of-chapter USMLE-style review questions, with answers and explanations, as well as new Clinical Application exercises , help students master the material.
Conceptual diagrams facilitate comprehension of difficult concepts and presents both normal and abnormal clinical conditions.
Active Learning Objectives, Chapter Summaries, and full-color artwork and tables facilitate learning and study.
A companion website offers additional resources for students including animations, additional review questions, additional clinical application exercises, advanced clinical problem-solving exercises, and suggested readings.''',
      link:
          'https://drive.google.com/uc?export=download&id=1ZYLikOEng-MmlA7YHkZxv1a1q2fZ8WcY'),
  Book(
      id: 38,
      subject: 'Physiology',
      title: 'Textbook of Medical Physiology',
      writer: 'Indu Khurana  (Author), Arushi Khurana (Author)',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41uxi78pEuL._SX382_BO1,204,203,200_.jpg',
      rating: 4.8,
      description:
          '''Prompted by the acceptance of the first edition, this endeavour of the author (the 2nd edition) incorporates thoroughly revised and updated text, organized into twelve sections arranged in three parts.
Part I: General Physiology – covers the text in five chapters of a section.
Part II: Systemic Physiology – comprises a total of ten sections, one on each body system.
Part III: Specialized Integrated Physiology – includes seven chapters arranged in a section.

• Text completed and updated with recent advances to cater the needs of postgraduates in Physiology.
• Quick introduction to functional anatomy followed by systematic presentation of the text is unique feature of this book.
• Inclusion of additional molecular and applied aspects makes the special features of this edition.
• Applied physiology, highlighted in the boxes, has been expanded and updated with recent concepts on pathophysiology and advances in basic and advanced investigations and therapeutic principles.
• Text and figures in an attractive four colored format.
• Illustrated with more than eleven hundred colored diagrams with many new additions.
• Complemented with numerous tables and flowcharts for quick comprehension.''',
      link:
          'https://drive.google.com/uc?export=download&id=1rT564GI_UwvI7Bty1GVZ0tyRk-U2gE8r'),
  Book(
      id: 39,
      subject: 'Physiology',
      title: 'Essentials of Medical Physiology',
      writer:
          'Sembulingam, K., Ph.D. (Author), Sembulingam, Prema, Ph.D. (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51LYgPt0GBL._SX371_BO1,204,203,200_.jpg',
      rating: 3.9,
      description: '''''',
      link:
          'http://93.174.95.29/main/1513000/0db7e1baf500b62bf5207c6f5160588c/K.%2C%20Ph.D.%20Sembulingam%2C%20Prema%2C%20Ph.D.%20Sembulingam%20-%20Essentials%20of%20Medical%20Physiology%2C%206th%20edition-Jaypee%20Brothers%20Medical%20Pub%20%282012%29.pdf'),
  Book(
      id: 40,
      subject: 'Physiology',
      title: 'Physiology at a Glance',
      writer: 'Jeremy P. T. Ward (Author), Roger W. A. Linden (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51N5gBrQXUL._SX392_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Extensively revised and updated, this fourth edition of Physiology at a Glance continues to provide a thorough introduction to human physiology, covering a wealth of topics in a comprehensive yet succinct manner. This concise guide breaks this often complex subject down into its core components, dealing with structures of the body from the cellular level to composite systems. New to this edition are three chapters on cell signalling, thermoregulation, and altitude and aerospace physiology, as well as a glossary of terms to aid medical, dental, health science and biomedical students at all levels of their training. Featuring clear, full-colour illustrations, memorable data tables, and easy-to-read text, Physiology at a Glance is ideal as both a revision guide and as a resource to assist basic understanding of key concepts.''',
      link:
          'https://drive.google.com/uc?export=download&id=1hlACDPXYbaFu4fonqubJnVhBV3iuPMub'),
  Book(
      id: 41,
      subject: 'Physiology',
      title: 'Comprehensive Textbook of Medical Physiology: Two Volume Set',
      writer: 'G. K. Pal (Author), Pravati Pal (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51%2B2NyZV5vL._SX360_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''This two volume set is a complete guide to medical physiology for undergraduate medical students. Beginning with a general overview of the subject the following chapters each provide in depth discussion on the physiology of each anatomical system. Each section covers both clinical and applied physiology with topics enhanced by numerous photographs and diagrams. The book features the following invaluable learning tools: Learning objective - defined at the start of each chapter Application boxes - key points of applied physiology highlighted in green boxes Clinical boxes - core concepts of related diseases and patient management highlighted in pink boxes Important notes - miscellaneous information that may be asked in viva voce examinations Chapter summary - each chapter ends with a two-part summary outlining key concepts of the topic and listing possible long and short questions, and viva questions that may be asked in examinations \'Scientist contributed\' boxes - explain historical links - highlighted in orange boxes''',
      link:
          'https://drive.google.com/uc?export=download&id=1wvfLF2NDNgo3XYCJwEt-jvIRepArscfy'),
  Book(
      id: 42,
      subject: 'Physiology',
      title: 'Medical Physiology',
      writer:
          'Boron MD PhD, Walter F. (Author), Boulpaep MD, Emile L. (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51gTKahz1JL._SX389_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''For a comprehensive understanding of human physiology - from molecules to systems -turn to the latest edition of Medical Physiology. This updated textbook is known for its unparalleled depth of information, equipping students with a solid foundation for a future in medicine and healthcare, and providing clinical and research professionals with a reliable go-to reference. Complex concepts are presented in a clear, concise, and logically organized format to further facilitate understanding and retention.

Clear, didactic illustrations visually present processes in a clear, concise manner that is easy to understand.
Intuitive organization and consistent writing style facilitates navigation and comprehension.
Takes a strong molecular and cellular approach that relates these concepts to human physiology and disease.
Student Consult eBook version included with purchase. This enhanced eBook experience includes access -- on a variety of devices -- to the complete text with thorough hyperlinking, images, 10 animations, and copious linkout notes prepared by the Editors.
An increased number of clinical correlations provides a better understanding of the practical applications of physiology in medicine.
Highlights new breakthroughs in molecular and cellular processes, such as the role of epigenetics, necroptosis, and ion channels in physiologic processes, to give insights into human development, growth, and disease.
Several new authors offer fresh perspectives in many key sections of the text, and meticulous editing makes this multi-authored resource read with one unified voice.
Your purchase entitles you to access the web site until the next edition is published, or until the current edition is no longer offered for sale by Elsevier, whichever occurs first. If the next edition is published less than one year after your purchase, you will be entitled to online access for one year from your date of purchase. Elsevier reserves the right to offer a suitable replacement product (such as a downloadable or CD-ROM-based electronic version) should online access to the web site be discontinued.''',
      link:
          'https://drive.google.com/uc?export=download&id=1oBQcSvBFABVxdGjlF1CDWqpACHtlPB15'),
  Book(
      id: 43,
      subject: 'Physiology',
      title: 'MCQs and EMQs in HUMAN PHYSIOLOGY',
      writer: 'Ian Roddie (Author), William F M Wallace (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41SdxxH3-IL._SX323_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''There has been a marked change in examination strategy over the last five years; EMQs (extended matching questions) are popular with tutors and students alike as they present a more realistic view of a student\'s ability to apply his or her knowledge in a clinical situation.



The new edition of MCQs in Physiology has been subject to a complete overhaul to become MCQs and EMQs in Physiology. This reflects the current methods of examination techniques and will provide the student with a complete revision resource book. Packed with MCQs and EMQs along with clear and simple explanations of each answer, this book covers all the main physiological systems. The questions stretch from basic to applied and interpretative and are written with the modern integrated syllabus firmly in mind.



Presented alongside other core revision books such as EMQs in Clinical Medicine this book will soon be seen as a must-have for any medic\'s shelf.''',
      link:
          'https://drive.google.com/uc?export=download&id=1BiM6ChXTp6Z3Fd1zXxHFupIAYn_zEquv'),
  Book(
      id: 44,
      subject: 'Physiology',
      title: 'Guyton & Hall Physiology Review (Guyton Physiology)',
      writer: 'Hall PhD, John E. (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/510T9EuxXPL._SX389_BO1,204,203,200_.jpg',
      rating: 3.8,
      description:
          '''The Guyton and Hall Physiology Review is the ideal way to prepare for class exams as well as the physiology portion of the USMLE Step 1. More than 1,000 board-style questions and answers allow you to test your knowledge of the most essential, need-to-know concepts in physiology.


Includes thorough reviews of all major body systems, with an emphasis on system interaction, homeostasis, and pathophysiology.
Designed as a companion to the 13th edition of Guyton and Hall Textbook of Medical Physiology, highlighting essential key concepts and featuring direct page references to specific questions.
Provides essential information needed to prepare for the physiology portion of the USMLE Step 1.
Student Consult eBook version included with purchase. This enhanced eBook experience includes the full text plus an interactive assessment section.''',
      link:
          'https://drive.google.com/uc?export=download&id=1GmvJh-k9Bwxk6ilDmrQ0JnpskY--pgp5'),
  Book(
      id: 45,
      subject: 'Physiology',
      title: 'Multiple-Choice Questions in Medical Physiology',
      writer: 'E.S.Prakash, (Author)',
      edition: '1st(revised 2014)',
      image:
          'https://s3.studylib.net/store/data/008927772_1-fad8aec6f537ae9949c01f3aa619e252.png',
      rating: 0.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1eb3D1Xe-t9Fcg7PlBMchL5NpbZcziCEx'),
  Book(
      id: 46,
      subject: 'Physiology',
      title: 'Physiology PreTest Self-Assessment and Review',
      writer: 'Patricia Metting(Author)',
      edition: '14th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/417qqpEZBEL._SX326_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''PreTest is the closest you can get to seeing the test before you take it
Great for course review and the USMLE Step 1!Physiology: PreTest asks the right questions so you\'ll know the right answers. Open it and start learning what\'s on the test.

500 USMLE-type questions and answers
What you really need to know for exam success
Detailed explanations for right and wrong answers
Tested and reviewed by students who recently passed their exams
STUDENT TESTED AND REVIEWED

"I like the High-Yield section in the beginning of the book. It\'s a nice quick review yet at the same time is thorough and includes the truly high-yield things to know for boards and class." -- Sheree Perron, Third-Year Medical Student, Eastern Virginia Medical School

"I found PreTest Physiology to follow fairly closely my experience with the USMLE Step 1 as far as question structure and depth of the material covered. The most basic and most commonly tested questions in physiology in each system were addressed as well as some of the finer details students still need to know." -- Daniel Marcovici, Third-Year Medical Student, Sackler School of Medicine, Tel Aviv University''',
      link:
          'http://93.174.95.29/main/1315000/6bcc123e22e3e2313abe643e10102d57/%28PreTest%20Basic%20Science%29%20Patricia%20Metting%20-%20Physiology%20PreTest%20Self-Assessment%20and%20Review-McGraw-Hill%20Medical%20%282013%29.pdf'),
  Book(
      id: 47,
      subject: 'Physiology',
      title: 'Rapid Review Physiology: With STUDENT CONSULT Online Access',
      writer: 'Brown MD, Thomas A. (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41bbcIp6DzL._SX351_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Get the most from your study time, and experience a realistic USMLE simulation, with Rapid Review Physiology, 2nd Edition, by Dr. Thomas A. Brown. This new reference in the highly rated Rapid Review Series is formatted as a bulleted outline with clinical images, tables and figures that make it easy to review all the physiology information you need to know for the USMLE. And with Student Consult online access, you can become familiar with the look and feel of the actual exam by taking a timed or a practice online test that includes 350 USMLE-style questions.

Review the most current information with completely updated chapters, images, and questions.
Profit from the guidance of series editor Dr. Edward Goljan, a well-known author of medical review books, who reviewed and edited every question.
Take a timed or a practice test online with more than 350 USMLE-style questions and full rationales for why every possible answer is right or wrong.
Access all the information you need to know quickly and easily with a user-friendly, two-color outline format that includes High-Yield Margin Notes.
Study and take notes more easily with the new, larger page size.
This edition thoroughly updated, including student and resident reviewer feedback to ensure relevancy and focus.
Practice with a new testing platform on the USMLE Consult testing engine that gives you a realistic review experience and fully prepares you for the exam.''',
      link:
          'http://93.174.95.29/main/1341000/8323457617a18832b4bf73e58f155227/Thomas%20A.%20Brown%20MD%20-%20Rapid%20Review%20Physiology_%20With%20STUDENT%20CONSULT%20Online%20Access%2C%202e-Mosby%20%282011%29.pdf'),
  Book(
      id: 48,
      subject: 'Physiology',
      title: 'Physiology - An Illustrated Review (Thieme Illustrated Reviews)',
      writer: 'Roger TannerThies  (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41on2WE8WhL._SX385_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''The perfect study tool for preparing for your courses or examinations - Physiology - An Illustrated Review\'s focused presentation and full-color illustrations makes learning the complex information essential to success easier. Sidebars make connections to underlying concepts in other basic sciences or apply the concepts presented in the clinical setting.

Features:

Succinct bullet-point text streamlines studying
Hundreds of full-color illustrations reinforce clear explanatory text
Numerous tables sum up crucial information for quick review
Frequent sidebars build on and integrate learning across the basic sciences and apply this learning to the clinical setting
200 review questions with a rationale for why answers are right or wrong test mastery and help you prepare for exams
An additional 200 review questions, all available online allow you to test yourself and get immediate feedback, quickly identifying areas for further study''',
      link:
          'http://93.174.95.29/main/2088000/a5ac8bec8bd555d0358590076c96106b/%28Thieme%20illustrated%20review%20series%29%20TannerThies%2C%20Roger%20-%20Physiology%20_%20an%20illustrated%20review-Thieme%20Medical%20Pub%20%282012%29.epub'),
  Book(
      id: 49,
      subject: 'Physiology',
      title: 'Physiology Cases and Problems (Board Review Series)',
      writer: 'Linda Costanzo (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41TK17c7BNL._SX348_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Physiology Cases and Problems, Fourth Edition is a collection of carefully selected patient case studies that cover the clinically relevant physiology topics that first and second year medical students need to know for physiology coursework and for the USMLE Step 1. Organized by body system, the book presents cases studies with questions and problems, followed by complete explanations and solutions including diagrams, graphs, and charts. Students may use this book alone, in small groups, or as a complement to BRS Physiology. Either way, it is intended to be a dynamic, working book that challenges its users to think more critically about physiologic principles.
This book includes a number of features to help students master the principles of physiology:
62 cases organized by body system to help students integrate material
Several expanded cases, including myasthenia gravis, atrioventricular conduction block, carbon monoxide poisoning, peptic ulcer disease, galactorrhea and amenorrhea, and prolactinoma
2 new cases on Chronic Renal Failure, Liver Failure and Hepatorenal Syndrome
New full-color interior, tables, and illustrations
Within each case, questions are arranged sequentially so that they intentionally build upon each other
Question difficulty varies from basic to challenging, recognizing the progression that most students make
Major equations are presented in boldface type, followed by explanations of all terms
Key topics are listed at the end of each case so that students may focus their study
Common Abbreviations are presented on the inside front cover, and normal values and constants are presented on the inside back cover
Online access to Ebook''',
      link:
          'http://93.174.95.29/main/1483000/ae9023823678b0b3b9697ddecb47c2e3/%28Board%20Review%20Series%29%20Linda%20Costanzo%20-%20Physiology%20Cases%20and%20Problems-LWW%20%282012%29.pdf'),
  Book(
      id: 50,
      subject: 'Physiology',
      title: 'BRS Physiology (Board Review Series)',
      writer: 'Linda S. Costanzo PhD(Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51UJxTKreuL._SX350_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''Be prepared—for the course and the Boards—withBRS Physiology, Sixth Edition.
This bestselling book provides over 350 USMLE-style questions with complete answers and explanations, chapter-ending exams and a comprehensive USMLE-format examination at the end of the book, and is enhanced by full-color illustrations and tables.
Offered in both print and online formats, the book boosts confidence and provides maximum accessibility and portability for in-class or on-the-go learning.
 • Maximize study time with the Board Review Series quick scan outline format.
 • Prepare for the Boards with more than 350 USMLE-style questions and answers.
 • Master core topics tested on the USMLE Step 1 exam with focused coverage of Key Physiology Topics and Key Physiology Equations.
 • See the connection between physiology and clinical medicine through clinical correlations.
 • Practice for the board examination using the comprehensive end-of-book exam.
 • Master key facts and information with the book’s full-color design, flow charts, illustrations, and tables that summarize information for convenient review.
 • Online interactive quiz bank that includes all the book’s questions for unlimited practice.''',
      link:
          'http://93.174.95.29/main/1556000/035c43c6a4126e4b4ae9e676229420e2/%28Board%20Review%20Series%29%20Linda%20S.%20Costanzo%20PhD%20-%20BRS%20Physiology-LWW%20%282014%29.pdf'),
  Book(
      id: 51,
      subject: 'Physiology',
      title: 'A Textbook of Practical Physiology',
      writer: 'C. L., M.D. Ghai',
      edition: '8th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/512CmsAwVuL._SX381_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''• Extensively revised and up-dated by incorporating the latest concepts and developments in the subject.
• Figures and text have been replaced and over twenty five new figures and diagrams have been added.
• Questions and answers added at the end of most of the experiments.
• A new feature of the book is the introduction of OSPEs at the end of most experiments.
• The section on Animal Experiments has been curtailed.
• The Appendix supplies a vast amount of Physiological Data.
•The book is meant primarily for MBBS, BDS and B.Ph.''',
      link:
          'http://93.174.95.29/main/1209000/57fdd766005dc5f4b710d66f61a7c5a2/C.%20L.%2C%20M.D.%20Ghai%20-%20A%20Textbook%20of%20Practical%20Physiology-Jaypee%20Brothers%20Medical%20Pub%20%282012%29.pdf'),
  Book(
      id: 52,
      subject: 'Physiology',
      title: 'Textbook of Physiology - Vol. 1 & 2',
      writer: 'A.K. Jain (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41t9h6NZ3SL._SX327_BO1,204,203,200_.jpg',
      rating: 3.9,
      description: '''Salient features of this textbook:
The entire text including the figures has been thoroughly revised and updated for all topics so as to achieve the requirements of the competency-based undergraduate curriculum.
Competency in each topic ((i.e. the student should be able to/must know areas of the study) have been added. Each chapter has been organized in the same way.
Sub-competencies within the topic which can be taught-together-aligned have also been added along with the preview.
New and modern concepts have been incorporated, simplified and presented so the text is easy to read and follow.
Study questions have been modified as per the requirement of the new Graduate Medical Education Regulation of the MCI.
Many more clinical pictures have also been incorporated for better understanding of the clinical concepts.
Self-testing is encouraged by the provision of multiple-choice questions (MCQs) at the end of each chapter.
This textbook contains 205 tables, more than 1350 study questions, 2500 MCQs and 825 figures including flow charts.''',
      link:
          'https://archive.org/download/akakkaakakakphyyyyssssiiiojajajaiiin/akakkaakakak%20Phyyyyssssiiio%20jajajaiiin.pdf'),
  Book(
      id: 53,
      subject: 'Pathology',
      title: 'Robbins & Cotran Pathologic Basis of Disease (Robbins Pathology)',
      writer:
          'Vinay Kumar MBBS MD FRCPath , Abul K. Abbas MBBS , Jon C. Aster MD PhD',
      edition: '9th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41X1CHvd-yL._SX369_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''Dependable, current, and complete, Robbins and Cotran Pathologic Basis of Disease, 9th Edition is the perennially best-selling text that you’ll use long after your medical student days are behind you. A world-class author team headed by Drs. Vinay Kumar, Abul Abbas, and Jon Aster, delivers the latest, most essential pathology knowledge in a readable, interesting manner, ensuring optimal understanding of the latest basic science and clinical content. High-quality photographs and full-color illustrations highlight new information in molecular biology, disease classifications, new drugs and drug therapies, and much more.

Rely on uniquely authoritative and readable coverage, ideal for USMLE or specialty board preparation, as well as for course work.
Simplify your study with an outstanding full-color, highly user-friendly design.
Stay up to date with the latest information in molecular and genetic testing and mechanisms of disease.
Consult new Targeted Therapy boxes online that discuss drug therapy for specific diseases.
Gain a new perspective in key areas thanks to contributions from new authors at the top of their fields.
Student Consult eBook version included with purchase. Further your understanding with access to a wealth of interactive ancillaries on the Student Consult site, including pathology case studies and videos and self-assessment questions.''',
      link:
          'https://drive.google.com/uc?export=download&id=1jSVbq4ZLHrR50q-sBrdteqfzMNMgtC9a'),
  Book(
      id: 54,
      subject: 'Pathology',
      title:
          'Fundamentals of Pathology by Hussain A,sattar (pathoma 2017 paperback &videos)',
      writer: 'Husain Sattar',
      edition: '2017 paperback',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51xYAa9X3pL._SX384_BO1,204,203,200_.jpg',
      rating: 3.1,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1awSa24R5ZocXJ87hgcxPv1gQTY8SeVA0'),
  Book(
      id: 55,
      subject: 'Pathology',
      title: 'Pathology Practical Book',
      writer: '(author)  Harsh Mohan',
      edition: '3rd',
      image:
          'https://d1w7fb2mkkr3kw.cloudfront.net/assets/images/book/lrg/9789/3509/9789350902660.jpg',
      rating: 3.8,
      description:
          '''This new edition has been fully revised to help pathology trainees acquire practical knowledge in diagnostic pathology. Divided into eight sections and consisting of 61 exercises, this useful guide discusses techniques and general pathology, and then offers exercises for each discipline within pathology - systemic pathology, cytopathology, haematology, clinical pathology and autopsy.



The third edition offers updated images and new exercises for topics of current clinical significance including immunohistopathology, surgical pathology, types of blood samples, anticoagulants and blood collection.



Supported by key points, nearly 600 line drawings, specimen photographs and photomicrographs, this practical manual also includes a CD reviewing specimens.







Key points





Fully revised, new edition offering trainees practical knowledge in diagnostic pathology
Consists of 61 exercises covering key disciplines within pathology
Includes updated images and new exercises for topics of current clinical significance
Includes key points, nearly 600 line drawings, specimen photographs and photomicrographs, and a CD reviewing specimens
Previous edition published in 2007''',
      link:
          'https://drive.google.com/uc?export=download&id=1awSa24R5ZocXJ87hgcxPv1gQTY8SeVA0'),
  Book(
      id: 56,
      subject: 'Pathology',
      title: 'Robbins basic pathology',
      writer:
          'by Vinay Kumar MBBS MD FRCPath (Author), Abul K. Abbas MBBS (Author), Jon C. Aster MD PhD (Author)',
      edition: '10th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41LCl6YDZKL._SX391_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''Part of the trusted Robbins and Cotran family, Robbins Basic Pathology provides a readable, well-illustrated and concise overview of the principles of human pathology that\'s ideal for today\'s busy students. This thoroughly revised edition continues with a strong emphasis on pathogenesis and the clinical features of disease, adding new artwork and more schematic diagrams to further aid in summarizing key pathologic processes and expand the already impressive illustration program.

Excellent art program boasts high-quality photomicrographs, gross photos, and radiologic images to supplement the world-class illustrations.
Bulleted summary boxes provide quick access to key information and easy review of key concepts.
Highlights pathogenesis, morphology, and pathophysiologic content throughout.
Includes increased and updated clinical topics.
New artwork and more schematic diagrams summarize key pathologic processes.
An all-star editorial team enables you to gain a rich understanding of all essential pathology concepts.
Student Consult eBook version included with purchase. This enhanced eBook experience allows you to search all of the text, figures, and images from the book on a variety of devices. You\'ll also access virtual microscope slides, self-assessment questions, additional images, updated pathology case studies, and Targeted Therapy boxes.''',
      link:
          'https://drive.google.com/uc?export=download&id=1rUrj2rm_oS_XH3DzmALUFqYezqGB7VXq'),
  Book(
      id: 57,
      subject: 'Pathology',
      title: 'Muir\'s Textbook of Pathology',
      writer: 'C. Simon Herrington (Editor)',
      edition: '15th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51RaNY4IpaL._SX380_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''Muir\'s Textbook of Pathology sets a standard in this subject by linking the scientific aspects that underlie pathological processes, relating these to specific organ systems and placing all in a context that the student of medicine or pathology can appreciate and understand.

The clearly defined and easy-to-follow structure, enhanced by numerous photographs and explanatory line diagrams, focus on core material without neglecting novel concepts and up-to-the minute detail. This one-stop-shop in pathology that will take the student right through medical school and beyond to postgraduate training.''',
      link:
          'https://drive.google.com/uc?export=download&id=1P0Fz_wiPK3YahqwmiYAeZdF-6UscqCGB'),
  Book(
      id: 58,
      subject: 'Pathology',
      title: 'Essentials of Rubin\'s Pathology',
      writer: 'Rubin MD, Emanuel (Author), Reisner PhD, Howard (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51OPz7uMCfL._SX382_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''Essentials of Rubin\'s Pathology, Sixth Edition, is a condensed version of the main title, Rubin\'s Pathology, 6e. Targeted to students in allied health fields, including dentistry, nursing, physical therapy, physician assistant, chiropractic, and occupational therapy, Essentials of Rubin\'s Pathology follows the same format as Rubin\'s Pathology, covering principles and mechanisms of pathology in the first section and organ-specific pathology in the second section. Essentials extracts key information on pathogenesis, epidemiology, and clinical features of diseases. Illustrations -- whether schematic or photographic -- are also all derived from the main text. A companion Website will offer the fully searchable online text, case studies, audio review questions, Podcasts, and an image bank and test generator for faculty.''',
      link:
          'http://93.174.95.29/main/936000/f894d821fc2b99b1e08c17edd2610d77/Howard%20Reisner%20PhD%2C%20Emanuel%20Rubin%20MD%20-%20Essentials%20of%20Rubin%27s%20Pathology-Lippincott%20Williams%20%26%20Wilkins%20%282013%29.pdf'),
  Book(
      id: 59,
      subject: 'Pathology',
      title:
          'Rubi\'s Pathology: Clinicopathologic Foundations of Medicine (Pathology (Rubin))',
      writer: 'Strayer MD PhD, David S. (Editor), Rubin MD, Emanuel (Editor)',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Ft3YXkhsL._SX382_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''Rubin’s Pathology sets the foundation for medical training and practice with expert coverage of disease processes and their effects on cells, organs, and individuals. Now in its Seventh Edition, the text is praised for being "exactly right for medical students" —a perfect balance of basic pathology and bedside perspective, without extraneous detail that’s beyond the boards.
Student-trusted features...
Thoroughly revised coverage including brand-new chapters on aging, autoimmune diseases, forensic pathology, pregnancy, and sepsis, plus extensively revised and expanded chapters on amyloidosis and obesity, diabetes mellitus and metabolic syndrome
An easy-to-navigate design featuring a new three-part organization, with 9 chapters covering mechanisms of disease, 6 chapters covering the pathogenesis of systemic conditions, and 19 chapters covering diseases of individual organ systems
More than 1700 images, including stunning new dynamic line drawings, plus micrographs and gross pathology images
Pathogenesis, Pathology, Pathophysiology, Epidemiology, Etiologic Agents, and Clinical Features sections are distinguished by helpful icons
Coverage of latest public health issues maintains currency and societal relevance
Bold key terms and bulleted lists reinforce key information
Bonus Online Resources:
For faculty: image bank and test generator
For students: case studies and podcasts''',
      link:
          'http://93.174.95.29/main/2225000/121f396503532f13082e9ef65a1346e1/David%20S.%20Strayer%2C%20Emanuel%20Rubin%20%28eds.%29%20-%20Rubin%E2%80%99s%20Pathology%20Clinicopathologic%20Foundations%20of%20Medicine-Wolters%20Kluwer%20%282015%29.pdf'),
  Book(
      id: 60,
      subject: 'Pathology',
      title: 'Textbook of Pathology with Pathology Quick Review and MCQs',
      writer: 'Harsh Mohan  (Author)',
      edition: '7th',
      image:
          'https://images-eu.ssl-images-amazon.com/images/I/51%2BSRp25v9L.jpg',
      rating: 2.9,
      description:
          '''The Textbook of PATHOLOGY depicts diagnostic pathology which has been growing exponentially with advances in molecular methods, cytogenetics and immunology, besides the ready availability of immunohistochemistry. Immunophenotyping and cytogenetics have been recommended as defining criteria for classification, diagnosis and prognostication of growing number of cancers. Basic morphologic pathology including recent knowledge of etiology and pathogenesis of diseases, and simultaneously the contribution of modern diagnostic techniques are explained in detail. Most of the topics include various aspects of diseases including their newer causes and recent mechanisms by insertion of latest information between the lines. Morphologic pathology is discussed with newer illustrations, while some old ones have been replaced with better quality images or improved after eliminating their shortcomings. One or more clinical cases with history and findings of examination have been given based on a common or an important disease pertaining to the respective systems.''',
      link:
          'https://drive.google.com/uc?export=download&id=1wKCCg4vvt576P5Lm4-4vKuHTmbPu_WDD'),
  Book(
      id: 61,
      subject: 'Pathology',
      title: 'Concise Pathology for Exam Preparation',
      writer: 'Geetika Khanna (Author))',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/61BR9pHxzhL._SX401_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''This book has been written in a concise and easily assimilable style to enable rapid understanding of the mechanism and morphology of disease. It has been structured in a question-answer format that incorporates information in numerous flowcharts and tables that are easy to tnagars001recall and duplicate in the examination. The new edition is based on Robbins and Cotran Pathologic Basis of Disease, 8E.

Updated high quality labeled photomicrographs now which can be used as an Atlas
Simple, precise and student-friendly text
Point-wise presentation for easy learning and quick recapitulation during examination
Line diagrams for basic understanding of the tissue/organ
Pencil sketches of sections (haematoxylin and eosin) along with salient points of identification, well integrated with text for understanding technical details of structures at the backdrop of theory
Practical section comprising of enlarged high quality labeled photomicrographs at the end of each chapter with detailed explanation based on students’ expectation to observe
Clinical correlation of certain important structures
Self-assessment exercise at the end of theory for revision of the topics studied''',
      link:
          'https://drive.google.com/uc?export=download&id=1YsYZ-U0ronobyF0-WNcTcvSTkgZVbdO3'),
  Book(
      id: 62,
      subject: 'Pathology',
      title: 'MCQs in Pathology',
      writer: '',
      edition: '',
      image: '',
      rating: 0.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1qD9X4_m6NqoX-xpQvH8MLOU_2WSGTTO9'),
  Book(
      id: 63,
      subject: 'Pathology',
      title: 'Lippincott\'s Illustrated Q&A Review of Rubin\'s Pathology',
      writer:
          'Bruce A. Fenderson  (Author), Raphael Rubin (Author), David S. Strayer (Author), Emanuel Rubin (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51GZjG37ypL._SX379_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''Lippincott Illustrated Q&A Review of Rubin\'s Pathology, Second Edition offers up-to-date, clinically relevant board-style questions-perfect for course review and board prep. Approximately 1,000 multiple-choice questions with detailed answer explanations cover frequently tested topics in general and systemic pathology. The book is heavily illustrated with photos in the question or answer explanation.
Online access to the questions and answers provides flexible study options.''',
      link:
          'http://93.174.95.29/main/742000/4e43382e8b7213cc794e59d1c392ca99/Bruce%20A.%20Fenderson%2C%20Raphael%20Rubin%2C%20David%20S.%20Strayer%2C%20Emanuel%20Rubin%20-%20Lippincott%27s%20Illustrated%20Q%26A%20Review%20of%20Rubin%27s%20Pathology-Lippincott%20Williams%20%26%20Wilkins%20%282010%29.pdf'),
  Book(
      id: 64,
      subject: 'Pathology',
      title: 'Review of Pathology and Genetics (PGMEE)',
      writer: 'Gobind Rai Garg and Sparsh Gupta (Author)',
      edition: '10th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/61mAjt-s1sL._SX373_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1rT4n4I10aXOzB8Hsixmw2gDEQttz_Bb5'),
  Book(
      id: 65,
      subject: 'Pharmacology',
      title: 'Essentials of Medical Pharmacology',
      writer: 'Tripathi KD',
      edition: '8th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41IQBQu0ySL._SX383_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Thoroughly revised chapters to include recent developments in theory and practice, as well as New Drugs released in India.
Latest therapeutic guidelines from authoritative sources like WHO, British National Formulary of India as well as from eminent professional bodies have been incorporated.
Important points are summarized in boxes for last minute revision.
A new feature ‘Problem directed study’ has been included at the end of majority of chapters to give an exercise in the therapeutic decision asking for a realistic clinical scenario.
The solutions provided in Appendix-1 explain how rational decisions could be arrived at.
Representative trade names of drugs with available dosage forms are mentioned.
Comprehensive chapter on drug interactions and an additional appendix on prescribing in pregnancy.
Recent innovations have been highlighted.
Enriched illustrations, flow charts and tables and boxed point-wise summaries of important aspects.
Comprehensive and systematic coverage of drugs, highlighting their therapeutic status.
Useful companion for medical students and professionals.''',
      link:
          'http://93.174.95.29/main/2274000/abd8031991dfdfffb4a2d14a5f7d0cbe/K.%20D.%20Tripathi%20-%20Essentials%20of%20Medical%20Pharmacology-Jaypee%20Brothers%20Medical%20Publishers%20%282018%29.pdf'),
  Book(
      id: 66,
      subject: 'Pharmacology',
      title: 'Pharmacology (Lippincott Illustrated Reviews Series)',
      writer:
          'Richard A. Harvey PhD (Author), Michelle A Clark PhD (Author), Richard Finkel PharmD (Author), Jose A. Rey PharmD BCPP (Author), Karen Whalen PharmD BCPS (Author)',
      edition: '5th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51ycsVc2hcL._SX383_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''Lippincott\'s Illustrated Reviews: Pharmacology, Fifth Edition enables rapid review and assimilation of complex information and focuses on the essentials of medical pharmacology. Clear, sequential pictures present  mechanisms of action and actually show, rather than tell, students how drugs work. This book features a signature outline format with more than 500 full-color illustrations and cross-references to other volumes in this bestselling, student-oriented series.''',
      link:
          'https://drive.google.com/uc?export=download&id=19bV-9ceKHzu3UpnZ7YWB4UCaFPnDLJnw'),
  Book(
      id: 67,
      subject: 'Pharmacology',
      title: 'Applied Biopharmaceutics & Pharmacokinetics',
      writer: 'Leon Shargel, Andrew B.C. Yu',
      edition: '7th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51DYvYt86vL._SX373_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''The landmark textbook on the theoretical and practical applications of biopharmaceutics and pharmacokinetics--now fully updated.''',
      link:
          'https://drive.google.com/uc?export=download&id=1I0ZKGfIgX_sT4u-7JPQYRyavB8yTo91O'),
  Book(
      id: 68,
      subject: 'Pharmacology',
      title: 'Quality by Design for Biopharmaceutical Drug Product Development',
      writer:
          'Feroz Jameel, Susan Hershenson, Mansoor A. Khan, Sheryl Martin-Moe (eds.)',
      edition: '1st Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51AyeMEkztL._SX331_BO1,204,203,200_.jpg',
      rating: 3.0,
      description:
          '''This volume explores the application of Quality by Design (QbD) to biopharmaceutical drug product development. Twenty-eight comprehensive chapters cover dosage forms, liquid and lyophilized drug products. The introductory chapters of this book define key elements of QbD and examine how these elements are integrated into drug product development. These chapters also discuss lessons learned from the FDA Office of Biotechnology Products pilot program. Following chapters demonstrate how QbD is used for formulation development ranging from screening of formulations to developability assessment to development of lyophilized and liquid formats. The next few chapters study the use of small-scale and surrogate models as well as QbD application to drug product processes such as drug substance freezing and thawing, mixing, sterile filtration, filling, lyophilization, inspection and shipping and handling.''',
      link:
          'https://drive.google.com/uc?export=download&id=1UwVoxisNZ3kxon9gBFHtCl8lzPvSSLH9'),
  Book(
      id: 69,
      subject: 'Pharmacology',
      title: 'Textbook of Pharmacognosy and Phytochemistry',
      writer: 'Biren Shah, Avinash Seth',
      edition: '',
      image:
          'https://secure-ecsd.elsevier.com/covers/80/Tango2/large/9788131234587.jpg',
      rating: 4.0,
      description:
          '''This comprehensive textbook is primarily aimed at the course requirements of the B. Pharm. students. This book is specially designed to impart knowledge alternative systems of medicine as well as modern pharmacognosy. It would also serve as a valuable resource of information to other allied botanical and alternative healthcare science students as well as researchers and industrialists working in the field of herbal technology.''',
      link:
          'https://drive.google.com/uc?export=download&id=1RhgW67NegbW8pSvSwBsEDBW3LxZtXnWO'),
  Book(
      id: 70,
      subject: 'Pharmacology',
      title: 'Trease and Evans Pharmacognosy',
      writer: 'William Evans',
      edition: '',
      image:
          'https://secure-ecsd.elsevier.com/covers/80/Tango2/large/9780702029332.jpg',
      rating: 4.3,
      description:
          '''Trease and Evans is an encyclopedic reference work on pharmacognosy - the study of those natural substances, principally plants, that find a use in medicine. Its popularity and longevity stem from the book\'s balance between classical (crude and powdered drugs characterization and examination) and modern (phytochemisty and pharmacology) aspects of this branch of science, as well as the editor\'s recognition in recent years of the growing importance of complementary medicines, including herbal, homeopathic and aromatherapy.''',
      link:
          'https://drive.google.com/uc?export=download&id=1UwVoxisNZ3kxon9gBFHtCl8lzPvSSLH9'),
  Book(
      id: 71,
      subject: 'Pharmacology',
      title: 'Fundamentals of Pharmacognosy and Phytotherapy',
      writer:
          'Michael Heinrich, Joanne Barnes, Simon Gibbons, Elizabeth M. Williamson',
      edition: '2nd Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/61QZRAl6T4L._SX378_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''A new classic in a new edition! Fully revised and updated throughout. New sections on antimicrobials. From journal reviews of the previous edition: Drawing on their wealth of experience and knowledge in this field, the authors, who are without doubt among the finest minds in pharmacognosy today, provide useful and fascinating insights into the history, botany, chemistry, phytotherapy and importance of medicinal plants in some of today\'s health care systems. This is a landmark textbook, which carefully brings together relevant data from numerous sources and provides in an authoritative and exhaustive manner, cutting edge information that is relevant to pharmacists, pharmacognocists, complementary practitioners, doctors and nurses alike.\' The Pharmaceutical Journal \'This is the first book that I have encountered which combines the compounds and plants found in standard pharmacognosy textbooks, i.e. those used in orthodox Western medicine, with the \'new phytopharmaceuticals\' which have become established in Western culture over the last 20 years. The medical establishment in this environment is finally catching up with the practices of the general population and so this book is an excellent choice for those who wish to investigate which of the many plants available have some scientific credence. I shall be adding this book to the Essential Reading list for all of the undergraduate students on our pharmacy degree course and would encourage all those involved in teaching pharmacy students to do the same." P.J. Houghton, Department of Pharmacy, King\'s College London, Journal of Ethnopharmacology \'Educated pharmacists no doubt equate Pharmacognosy with hours spent hunched over a microscope identifying vegetable drugs. Many probably consider it as a subject with little importance in a modern pharmacy curriculum. How wrong they are! ... This book is designed to give an overview at an easy-to-understand level of a broad subject area... For students of science and of the healthcare professions it is a useful text and the authors are to be commended for their work.\' Irish Pharmacy Journal From customer reviews: \'A new classic. This is an excellent publication both for science students and the non scientific who have an interest in phytotherapy. The layout is logical and clearly set out. I love the chemical structural diagrams, and the explanations of even complex sequences are easy to understand with very little jargon. It is encouraging to see pharmacognosy being given a prominent place in a modern textbook, and interesting to see both hand drawings and chemical structures on the same page!I can recommend this to anyone who is interested in the science behind herbal products and medicines; especially if you are interested in plants.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Tew1FDinpwsZNLkhYgO9DfuGKY-I6YC9'),
  Book(
      id: 72,
      subject: 'Pharmacology',
      title: 'Color Atlas of Pharmacology',
      writer:
          'Heinz Luellmann  (Author), Klaus Mohr (Author), Lutz Hein (Author), Detlef Bieger (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41ft5XU%2B6ML._SX329_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Updated with the most important new substances and scientific developments, the third edition of The Color Atlas of Pharmacology makes it easier than ever for students, nurses, and practicing physicians to keep up with the latest developments in this constantly changing field. Featuring a user-friendly layout, jargon-free language, and more than 160 spectacular color charts and illustrations, the atlas is divided in to four, color-coded sections:
Part 1 - General pharmacology - includes descriptions of substance formulation, absorption, distribution, elimination, and molecular mechanisms of action

Part 2 - Systems pharmacology - with special emphasis on the functional and therapeutic aspects of a wide range of medicinal agents

Part 3 - Therapy of selected diseases - such as osteoporosis, acute myocardial infarction, migraine, asthma, tropical diseases, and many more

Part 4 - Drug Index - helpfully listed by substance, generic, and brand names

Concise, portable, and packed with information, the third edition of The Color Atlas of Pharmacology is the most practical first-stop reference for today\'s busy healthcare professional.''',
      link:
          'http://93.174.95.29/main/57000/cc789036fab2d657a9bd53d387af4f9c/Heinz%20Luellmann%2C%20Klaus%20Mohr%2C%20Lutz%20Hein%2C%20Detlef%20Bieger%20-%20Color%20Atlas%20of%20Pharmacology-Thieme%20%282005%29.pdf'),
  Book(
      id: 73,
      subject: 'Pharmacology',
      title: 'Basic & Clinical Pharmacology',
      writer: 'Bertram G. Katzung',
      edition: '14th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51LC1EkBFZL._SX388_BO1,204,203,200_.jpg',
      rating: 3.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1XR6cxxTw-I9w6xuzQuhSltjseRD_8xfJ'),
  Book(
      id: 74,
      subject: 'Pharmacology',
      title: 'Rang & Dale\'s Pharmacology',
      writer:
          'Ritter DPhil FRCP FBPharmacolS FMedSci, James M. (Author), Flower PhD DSc FBPharmacolS FMedSci FRS, Rod J. (Author), Henderson BSc PhD FBPharmacolS FSB, Graeme (Author), Loke MB BS MRCP MD, Yoon Kong (Author), & 2 more',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51PbaMn2HzL._SX388_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Comprehensive yet easy to use, Rang and Dale’s Pharmacology has been providing core basic and clinical science information to students and healthcare practitioners worldwide for more than 25 years. The fully revised 9th Edition keeps you up to date with all that’s new in the field, including new and emerging drugs and recent studies. From cover to cover, you’ll progressively increase your knowledge of all relevant aspects of pharmacology, from a molecular understanding of receptors and drug actions through clinical uses of key groups of drugs.

Keeps you up-to-date with new information in this fast-changing field, including significantly revised coverage of CNS drugs, cognitive enhancers, anti-infectives, biologicals/biopharmaceuticals, lifestyle drugs, and more.
Includes access to unique features online, including more than 100 brand new chapter-specific multiple-choice questions and 6 new cases for immediate self-assessment.
Features a color-coded layout for faster navigation and cross-referencing.
Clarifies complex concepts with Key Points boxes, Clinical Uses boxes and full-color illustrations throughout.
Enhanced eBook version included with purchase. Your enhanced eBook allows you to access all of the text, figures, and references from the book on a variety of devices.''',
      link:
          'https://drive.google.com/uc?export=download&id=1uqySksiKuhrV0FqcRE071zyG9hwaCZ4a'),
  Book(
      id: 75,
      subject: 'Pharmacology',
      title: 'Katzung & Trevor\'s Pharmacology: Examination & Board Review',
      writer: 'Marieke Kruidering-Hall, PhD,Anthony J. Trevor, PhD',
      edition: '12th',
      image:
          'https://accessmedicine.mhmedical.com/data/books/2465/cover_9781259641022_fc.jpeg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=179nLnuhhZYvmvcfJ4C4N2atv7s3gmOnI'),
  Book(
      id: 76,
      subject: 'Pharmacology',
      title: 'Color Atlas of Pharmacology',
      writer: 'Albrecht Ziegler',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41ZdLeOQzUL._SX312_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1zVQgpuWujGnZ4FCGGa5f0FmjULhsMOh3'),
  Book(
      id: 77,
      subject: 'Pharmacology',
      title: 'Pharmacology for the Health Care Professions',
      writer: 'Christine M. Thorp (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41siVf93QgL._SX346_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1YU_whEDjOrkHlm5WHm9pRe71uafeJ7iQ'),
  Book(
      id: 78,
      subject: 'Pharmacology',
      title: 'Pharmacotherapy: A Pathophysiologic Approach',
      writer: 'DiPiro, Joseph, Talbert, Robert, Yee, Gary, Matzke, Gary,',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41eiWVkxdhL._SX365_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1Do1ySRG-LASLUTBVqQgJJU5UpPEeJmty'),
  Book(
      id: 79,
      subject: 'Pharmacology',
      title: 'Herbal Medicines',
      writer:
          'Dr Joanne Barnes (Author), Dr Linda A. Anderson (Author), Prof J.D. Phillipson (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51aw6hdNmXL._SX396_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Herbal medicinal products are increasing in popularity in the developed world although there are many concerns about their quality, safety and efficacy. "Herbal Medicines" provides a comprehensive single source of scientifically rigorous, impartial information on over 150 of the most commonly used herbal medicinal products. This third edition has been extensively revised and updated. It aims to answer the questions raised for the healthcare professional by providing scientifically rigorous, impartial information on medical herbs.''',
      link:
          'https://drive.google.com/uc?export=download&id=1DqCi2PJ4AMu250M3LoAmsdgV6k31hFQB'),
  Book(
      id: 80,
      subject: 'Pharmacology',
      title: 'Medical Pharmacology at a Glance',
      writer: 'Michael J. Neal (Author)',
      edition: '8th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51LZuw0CMuL._SX388_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Medical Pharmacology at a Glance is recognised as an excellent starting point for pharmacology study. This international best-seller is the perfect companion for all medical and health students, providing an accessible, visual overview of pharmacology. This 8th edition has been extensively updated, especially in the areas of anaesthetics, drugs used in AIDs, cardiovascular drugs, drugs used in anxiety, depression and schizophrenia, urological drugs, drug metabolism, as well as practical concerns such as drug indications and side effects. Ideal for USMLE and pharmacology exam revision, Medical Pharmacology at a Glance features: The basic principles of drug action, interaction, absorption and excretion Chapters based on diseases or syndrome, for efficient clinical learning An emphasis on drug mechanisms References to the pathophysiology of disease, to aid understanding of drug choice and action Case studies with questions and full explanation of answers A companion website at www.ataglanceseries.com/pharmacology featuring online cases and flashcards''',
      link:
          'https://drive.google.com/uc?export=download&id=142ijVrkpmi47wuN7Brdtmb_QfbmV8fXU'),
  Book(
      id: 81,
      subject: 'Pharmacology',
      title: 'Lange Pharmacology Flashcards',
      writer: 'Suzanne Baron (Author), Christoph Lee  (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51MHSl2SrRL._SX356_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''A fun, fast, portable review of pharmacology for the USMLE Step 1

Written by former medical students at Yale University, LANGE Pharmacology Flash Cards, Fourth Edition offer concise, yet complete coverage of the subject. Each card covers a specific disease or drug, with high-yield facts in bold. Every card also includes a clinical vignette on the flip side which helps students answer the question “when is this medication the answer in real-world clinical practice?”

·         200 two-sided cards in the deck

·         Essential for board review and coursework

·         Created by medical students for medical students

·         Clinical vignettes show students how important concepts relate to real-world practice''',
      link:
          'https://drive.google.com/uc?export=download&id=1C4KE24beDOkZE0ikZjEUw7QFYm2tPSxq'),
  Book(
      id: 82,
      subject: 'Pharmacology',
      title: 'Goodman and Gilman\'s The Pharmacological Basis of Therapeutics',
      writer:
          'Laurence Brunton (Author), Bjorn Knollmann (Author), Randa Hilal-Dandan (Author)',
      edition: '13th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41tlQ87DKAL._SX370_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''The gold-standard of pharmacology texts – updated to reflect the latest developments and breakthroughs

Goodman & Gilman’s: The Pharmacological Basis of Therapeutics, Thirteenth Edition represents the pinnacle of authority and accuracy in describing the actions and uses of therapeutic agents in relation to physiology and pathophysiology. Goodman & Gilman’s careful balance of basic science and clinical application has guided thousands of practitioners and students to a clear understanding of the drugs essential to preventing, diagnosing, and treating disease.

Enhanced by a full-color presentation and updated to reflect all critical new developments in drug action and drug-disease interaction, the Thirteenth Edition includes more than 440 color illustrations depicting key principles and actions of specific pathways and therapeutic agents. This edition also includes new chapters on hypertension therapy, myocardial ischemia therapy, treatment of pulmonary arterial hypertension, immunostimulants and vaccines, and treatment of viral hepatitis, along with appendices on prescription order writing, patient compliance, and pharmacokinetics

Goodman & Gilman’s The Pharmacological Basis of Therapeutics, Thirteenth Edition is divided into nine sections, covering:

• General Principles
• Neuropharmacology
• Modulation of Pulmonary, Renal, and Cardiovascular Function
• Inflammation, Immunomodulation, and Hematopoiesis
• Endocrine Pharmacology
• Gastrointestinal Pharmacology
• Chemotherapy of Infectious Disease
• Chemotherapy of Neoplastic Diseases
• Special Systems Pharmacology''',
      link:
          'https://drive.google.com/uc?export=download&id=1FN95qAqAHFFST4i0PXhcaQ7jgjRpWkLE'),
  Book(
      id: 83,
      subject: 'Pharmacology',
      title: 'Review of Pharmacology (PGMEE) Paperback – 2018',
      writer: 'Gobind Rai Garg',
      edition: '12th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/61w8ScOSXJL._SX386_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''Thoroughly revised and Updated edition including all recent questions, controversial questions, concept-based questions and image-based questions of 2017-19.
New NBE based pattern (Wider coverage, Concept development, One-liner approach, Value-based MCQs, Applied aspect MCQs, Image based MCQs, Updated Golden Points).
Newly added 130 plus Images, Flowcharts and Diagrams.
Facts and concepts from latest editions of Park 25th, Leon Gordis Epidemiology 4th and Mahajan Biostatistics 9th.
Explained referenced answers of all recent questions of 2019 to 2012, All India (2012-1991), AIIMS (Nov 2018-1991), DNB (2012-1991), AP, JIPMER, Bihar, UPSC CMS (2018-1991) and other state exams (2018-1991).
Theory given at start of each chapter. Theory chapter, topic-wise, one-liner points, previous MCQs highlighted as “Q”.
Key Revision Point Boxes given on side of each topic for Must-Know MCQ facts.
Solved MCQs (1991-2019) including ALL "NEET pattern MCQs (2017-19).
Recent/New Topics and Changing Concepts in PSM: New Initiatives (Indian): Ayushman Bharat 2018, Anemia Mukt Bharat 2018, Swacch Bharat Mission, National Nutrition Mission (NNM) 2017-18, National Strategic Plan for Malaria Control in India (NVBDCP) 2017-22, National Strategic Plan for Tuberculosis Control 2012-2017, Accelerated Plan for Elimination of Lymphatic Filariasis (APELF) India 2018, National Program for Prevention and Control of Fluorosis (NPPCF) 2014, Td Vaccination Guidelines 2018-19 New Initiatives (Global):Global Program to Eliminate Lymphatic Filariasis (GP ELF), Global Health Sector Strategy on Viral Hepatitis 2016-2021, EYE Strategy, Global Eye Health Action Plan 2014-19, Global Strategy for Women\'s Children\'s and Adolescent\'s Health 2016-2030, Integrated Global Action Plan for Prevention and Control of Pneumonia and Diarrhoea {GAPPD), Global Technical Strategy for Malaria (2016-2030) New Topics in Public Health: Tribal health in India, Health Index of India, Global Hunger Index (GHI), IMA Guidelines on Period of Viability, Delayed immunization Limits (NIS), BMW categorization, Nutrition Rehabilitation Centres (NRCs), Contraception and Adolescence, Health Care and System, Adjuvants in Vaccines New Topics in Disease Control: Measles treatment, Diphtheria treatment, Chicken pox vaccines, TB Facts Epidemiology, TB and Co-morbidities, IPV vs flPV, Diarrhoea control measures, Rota virus vaccine, Dengue diagnosis, Malaria epidemiology, Treatment of Severe/Complicated Malaria, Active Surveillance in Kala Azar, Lifestyle Modifications to Manage Hypertension, Vision Impairment, Oral diseases, Key Population Groups in Global Plan 90-90-90Targets for TB New Guidelines: RNTCP Guidelines 2018-19 (Treatment of Drug Resistant TB, Intensified TB case finding, Newer Anti-TB drugs, Category II treatment guidelines), NEW NPEP Guidelines 2018-19 (AFP Surveillance Indicators), NEW RCH Program Guidelines 2018-19 (New Initiatives in Family Planning, National Family Planning Indemnity Scheme, Post-natal visits guidelines), NEW NACP Guidelines 2018-19 (CD4 treatment criteria), NEW NVBDCP Guidelines 2018-19 (Kala azar treatment, Malaria treatment), NEW NPCB Guidelines 2017-18 (New Blindness Criteria), NEW ARI Guidelines 2017-18, NEW Hl Nl Categorization Guidelines in India 2018-19, NEW National Immunization Schedule {NIS) 2018-19, NEW BMW Treatment Standards in India 2018-19, NEW Incentive Packages under National Health Programmes 2018-19, NEW Emergency Response Support System (ERSS) 2019-20, NEW Health-related Targets under Union Budget of India 2017-18, NHP 2017, SDGs 2015-2030, NEW Specific Targets for SDG Target 3.3 on Infectious Diseases, NEW Developed Vaccines (Dengue, Leprosy, Malaria, Rabies, MR), NEW WHO Rabies Vaccination Guidelines 2018, NEW WHO Uniform MDT Guidelines 2018-19, NEW WHO-UNICEF BFHI Guidelines 2018-19, NEW WHO Groups of Drugs for Drug-resistant TB 2016-17, NEW WHO Cancer Data (World, India) 2018, NEW WHO ICD-11 Classification 2018, NEW International Death Certificate (IDC) Format 2018-19, NEW Goalposts to construct HDI Index 2018-19, NEW Poverty Criteria (Multidimensional Poverty Index MDPI), NEW AHA Revised Jones Criteria for Diagnosis of Rheumatic Fever 2015. New Policies and Legislations: Open Vial Policy 2015, The Rights of Persons with Disabilities Bill 2016-17, National Health Policy 2017.
Updated Concepts: Evidence Based Medicine, Meta-analysis, Systematic reviews.
Updated compilation of Rural Health Statistics India 2018 and Public Health Statistics of India 2018-19.
Important Annexures have been provided in the beginning of the book to give the student an edge over others.
Author E-support Get regular updates on PSM and Info for Live Lectures by Dr Vivek Jain.''',
      link:
          'http://93.174.95.29/main/2283000/119bc03c47752e84289a369ea77cc769/Gobind%20Rai%20Garg%20-%20Review%20of%20Pharmacology%20%28PGMEE%29%20Paperback%20%E2%80%93%202018-JAYPEE%20BROTHERS%20MEDICAL%20PUBLISHERS%20%282018%29.pdf'),
  Book(
      id: 84,
      subject: 'Pharmacology',
      title: 'MCQs in Pharmacology',
      writer: 'G. Vidya Sagar (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41w6rd5l4wL._SX236_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1WeoZ-jKyOA95Q-5YB_j4zjjtTxy55ZlU'),
  Book(
      id: 85,
      subject: 'Biochemistry',
      title:
          'Lippincott Illustrated Reviews: Biochemistry (Lippincott Illustrated Reviews Series)',
      writer: 'Denise Ferrier (Author)',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51jkWr2pTUL._SX382_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''Lippincott Illustrated Reviews: Biochemistry is the long-established, first-and-best resource for the essentials of biochemistry. Students rely on this text to help them quickly review, assimilate, and integrate large amounts of critical and complex information. For more than two decades, faculty and students have praised this best-selling biochemistry textbook for its matchless illustrations that make concepts come to life.
Master all the latest biochemistry knowledge, thanks to extensive revisions and updated content throughout, including an expanded chapter on macronutrients, a completely new chapter on micronutrients, and much more. A bonus chapter on blood clotting with new, additional questions is included online.
See how biochemistry applies to everyday healthcare through integrative, chapter-based cases as well as “Clinical” boxes throughout.
Learn and study effortlessly with a concise outline format, abundant full-color artwork, and chapter overviews and summaries.
Look for icons that signal an animation at thePoint or an integrative clinical case in the Appendix.
Assess and reinforce your learning with more than 200 new review questions available online.''',
      link:
          'https://drive.google.com/uc?export=download&id=15ZEBHYuHUeDpicpljpti-NvXxM0Jt-uc'),
  Book(
      id: 86,
      subject: 'Biochemistry',
      title: 'Biochemistry',
      writer: 'Satyanarayana M.Sc. Ph.D. F.I.C. F.A.C.B.',
      edition: '4th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51xOaXyEM4L._SX388_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''This textbook ‘Biochemistry’ has become one of the most preferred text books (in India and many other countries) for the students as well as teachers in medical, biological and other allied sciences. The book has undergone three editions, several reprints, and revised reprints in a span of 13 years.

There are many biochemistry textbooks in the market. Some of them are purely basic while others are applied, and there are very few books which cover both these aspects together. For this reason, the students learning biochemistry in their undergraduate courses have to depend on multiple books to acquire a sound knowledge of the subject.

This book, ‘Biochemistry’ is unique with a simultaneous and equal emphasis on basic and applied aspects of biochemistry. This textbook offers an integration of medical and pure sciences, comprehensively written to meet the curriculum requirements of undergraduate courses in medical, dental, pharmacy, life-sciences and other categories (agriculture, veterinary, etc.).

This book is designed to develop in students a sustained interest and enthusiasm to learn and develop the concepts in biochemistry in a logical and stepwise manner. It incorporates a variety of pedagogic aids, besides colour illustrations to help the students understand the subject quickly and to the maximum. The summary and biomedical/clinical concepts are intended for a rapid absorption and assimilation of the facts and concepts in biochemistry. The self-assessment exercises will stimulate the students to think rather than merely learn the subject. In addition, these exercises (essays, short notes, fill in the blanks, multiple choice questions) set at different difficulty levels, will cater to the needs of all the categories of learners.

New to This Edition

The book offers an integration of medical and pure sciences, and is comprehensively written, revised and updated to meet the curriculum requirements of Medical, Pharmacy, Dental, Veterinary, Biotechnology, Agricultural Sciences, Life Sciences, and others studying Biochemistry as one of the subjects.
It is the first text book on Biochemistry in English with multi-colour illustrations by an author from Asia. The use of multicolours is for a clearer understanding of the complicated biochemical reactions.
It is written in a lucid style with the subject being presented as an engaging story growing from elementary information to the most recent advances, and with theoretical discussions being supplemented with illustrations, flowcharts, and tables for easy understanding of Biochemistry.
It has each chapter beginning with a four-line verse followed by the text, biomedical concepts, a summary, and self-assessment exercises. The lively illustrations and text with appropriate headings and sub-headings in bold type faces facilitate reading path clarity and quick recall.
It provides the most recent and essential information on Molecular Biology and Biotechnology, Diabetes, Cancer, Free Radicals, Free radicals and Antioxidants, Prostaglandins, etc.
It describes a wide variety of case studies and biochemical correlations and several newer biomedical aspects- Metabolic syndrome, Therapeutic diets, Atkins diet, Trans fatty acids, Epigenetics, Nutrigenomics, Recombinant ribozymes, Membrane transport disorders, Pleural fluid etc.
It contains the basics (Bioorganic and Biophysical Chemistry, Tools of Biochemistry, Immunology, and Genetics) for beginners to learn easily Biochemistry, origins of biochemical words, confusables in Biochemistry, principles of Practical Biochemistry, and Clinical Biochemistry Laboratory.''',
      link:
          'https://drive.google.com/uc?export=download&id=1m37Brw2FHnUw0rmpZ--z_e_RjYxR7kc3'),
  Book(
      id: 87,
      subject: 'Biochemistry',
      title: 'Textbook of Biochemistry for Medical Students',
      writer: 'D.M. Vasudevan, S. Sreekumari, V. Kannan',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51qp3vfYTGL._SX361_BO1,204,203,200_.jpg',
      rating: 4.4,
      description: '''More student-friendly edition.
• Content has been made lesser in this textbook.
• 30% of the needless content has been reduced to end the burden of extra details from the average students.
• Remarkable improvement in the readability of the book with a use of increased font size.
• Chapters on clinical chemistry have been extensively updated.
• Major attraction is the incorporation of clinical case studies in almost all chapters to identify clinical relevance of Biochemistry.
• Clinically relevant points are added in most of the chapters.
• Covers advances made in the area of molecular biology during past few years.
• Essay questions, short notes, multiple choice questions and viva voce type questions are given at the end of almost every chapter, ideal for last-minute preparation of examinations.
• Addition of about 1000 figures, 200 tables and 200 boxes.
• Quality of paper is also improved during successive editions.
• Revision booklet now added as a part of the main text.''',
      link:
          'http://93.174.95.29/main/1322000/68567fddeea321f3a3100a4cca3a5864/D.%20M.%20Vasudevan%2C%20S.%20Sreekumari%2C%20Kannan%20Vaidyanathan%20-%20Textbook%20of%20Biochemistry%20for%20Medical%20Students-Jaypee%20Brothers%20Medical%20Publishers%20%282013%29.pdf'),
  Book(
      id: 88,
      subject: 'Biochemistry',
      title: 'Harpers Illustrated Biochemistry',
      writer:
          'Victor W. Rodwell, David Bender, Kathleen M. Botham, Peter J. Kennelly, P. Anthony Weil',
      edition: '31th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51URA2D4d2L._SX387_BO1,204,203,200_.jpg',
      rating: 4.4,
      description: '''Synopsis
Expand/Collapse Synopsis
Gain a thorough understanding of the principles ofbiochemistry as they relate to the study of clinical medicine
A Doody\'s Core Title for 2017!

THE BEST REVIEW FOR THE USMLE!

The Thirtieth Edition of Harper’s Illustrated Biochemistry combines outstanding full-colorillustrations with authoritative integrated coverage of biochemical disease and clinical information. Using brevity and numerous medically relevant examples, Harper\'s presents a clear, succinct review of the fundamentals of biochemistry that every student must understand in order to succeed in medical school.

All fifty-eight chapters emphasize the medical relevance of biochemistry

Full-color presentation includes more than 600 illustrations
Each chapter includes a section on BiomedicalImportance and a summary of the topics covered
Review questions follow each of the eleven sections
Case studies in every chapter emphasize the clinical relevance to biochemistry
NEW coverage of toxic naturally-occurring amino acids; extraterrestrial biomolecules; computer-aided drug design; the role of complement cascade in bacterial and viral infection; secreted mediators of cell-cell signaling between leukocytes; the role of mast cells, basophils, andeosinophils; and the hazard of antioxidants that down-regulate radical signaling for apoptosis and increase risk of cancer
Applauded by medical students for its current and engaging style, Harper\'s Illustrated Biochemistry is an essential for USMLE review and the single best reference for learning the clinical relevance of any biochemistry topic.''',
      link:
          'https://drive.google.com/uc?export=download&id=1DMycIM0LQYjUSvtPGbRzdK-CA3MUAUXa'),
  Book(
      id: 89,
      subject: 'Biochemistry',
      title: 'Principles of Medical Biochemistry',
      writer:
          'Meisenberg PhD, Gerhard (Author), Simmons PhD, William H. (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51UwHVbtj3L._SX389_BO1,204,203,200_.jpg',
      rating: 3.4,
      description:
          '''"Highly Commended," Basic and Clinical Sciences Category, British Medical Association 2012 Medical Book Competition

Access the fully searchable text online at www.studentconsult.com, along with downloadable illustrations, 150 USMLE-style test questions, 20 clinical case studies, chapter summaries, and integration links to related subjects.
Understand biochemistry, cell biology, and genetics together in context through an integrated approach.
Get only the information you need for your course with comprehensive yet focused coverage of relevant topics.
Review and reinforce your learning using the glossary of technical terms, highlighted in the text and with interactive features online.
Tap into the most up-to-date coverage of new developments in genome research, the molecular basis of genetic diseases, techniques of DNA sequencing and molecular diagnosis, RNA interference as a mechanism both for regulation of gene expression and for anti-viral defense, and more.
Gain a clear visual understanding through new and updated figures that provide current and relevant guidance.
Make the link between basic science and clinical medicine with new Clinical Example boxes in nearly every chapter.
Focus on the most essential biochemistry principles and how they apply to clinical medicine''',
      link:
          'https://drive.google.com/uc?export=download&id=1L2FRCNeWkzQSIHSdgr5ohVEnOOknOjHC'),
  Book(
      id: 90,
      subject: 'Biochemistry',
      title: 'Recent Advances in Biochemistry',
      writer: 'Harold H. Trimm, William Hunter Jr',
      edition: '1ST',
      image:
          'https://images.tandf.co.uk/common/jackets/amazon/978192669/9781926692722.jpg',
      rating: 3.4,
      description:
          '''Advances in biochemistry directly influence medicine and the field of human health. The field of biochemistry is constantly changing with new discoveries being made all the time. This new book covers a range of advances in the field of biochemistry, including new research techniques and methods, a classification system, new research, and more.''',
      link:
          'https://drive.google.com/uc?export=download&id=1jzzkG0xvRenXS8rbl2x8Wq060UfYBaLI'),
  Book(
      id: 91,
      subject: 'Biochemistry',
      title: 'Essentials of Biochemistry',
      writer: 'Herbert J. Fromm, Mark Hargrove (auth.)',
      edition: '1ST',
      image:
          'https://image.slidesharecdn.com/essentialsofbiochemistry-150115150340-conversion-gate02/95/essentials-of-biochemistry-1-638.jpg',
      rating: 3.4,
      description:
          '''This textbook, Essentials of Biochemistry is aimed at chemistry and biochemistry undergraduate students and first year biochemistry graduate students. It incorporates the lectures of the authors given to students with a strong chemistry background. An emphasis is placed on metabolism and reaction mechanisms and how they are studied. As the title of the book implies, the text lays the basis for an understanding of the fundamentals of biochemistry.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Q7KS4Ex5aEdPzAU7AxNNQHhqzu5e88GD'),
  Book(
      id: 92,
      subject: 'Biochemistry',
      title: 'Medical Biochemistry at a Glance',
      writer: 'J. G. Salway  (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51zSIkTQUpL._SX395_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''Offering a concise, illustrated summary of biochemistry and its relevance to clinical medicine, Medical Biochemistry at a Glance is intended for students of medicine and the biomedical sciences such as nutrition, biochemistry, sports science, medical laboratory sciences, physiotherapy, pharmacy, physiology, pharmacology, genetics and veterinary science. It also provides a succinct review and reference for medical practitioners and biomedical scientists who need to quickly refresh their knowledge of medical biochemistry.
The book is designed as a revision guide for students preparing for examinations and contains topics that have been identified as \'high-yield\' facts for the United States Medical Licensing Examination (USMLE), Step 1.

This third edition:

Has been thoroughly revised and updated and is now in full colour throughout
Is written by the author of the hugely successful Metabolism at a Glance (ISBN 9781405107167)
Features updated and improved clinical correlates
Expands its coverage with a new section on Molecular Biology
Includes a brand new companion website of self-assessment questions and answers at www.ataglanceseries.com/medicalbiochemistry''',
      link:
          'https://drive.google.com/uc?export=download&id=1uyjPw21hvRIGUg9K9RapvrDZx-kMnGl-'),
  Book(
      id: 93,
      subject: 'Biochemistry',
      title: 'Fundamentals of Biochemistry',
      writer: 'J.L. Jain',
      edition: '1ST',
      image:
          'https://image.slidesharecdn.com/fundamentalsofbiochemistrybyjain-150606022052-lva1-app6892/95/fundamentals-of-biochemistry-by-jain-1-638.jpg',
      rating: 3.4,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1lyFvWXE2gXDeckyuRs9C0nUbPl9aOzPA'),
  Book(
      id: 94,
      subject: 'Biochemistry',
      title: 'Color Atlas of Biochemistry',
      writer: 'Jan Koolman  (Author), Klaus-Heinrich Röhm  (Author)',
      edition: 'revised 2nd ed',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/4115%2BbltoHL._SX331_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''Extraordinary color illustrations make biochemistry concepts easy to understand and retain

Providing a powerful visual overview of the entire spectrum of human biochemistry, the third edition of the popular Color Atlas of Biochemistry is an ideal reference and study aid. It utilizes the signature "Flexibook" format, consisting of double-page spreads with clear explanatory text on the left-hand page and exquisitely detailed full-color graphics on the right. These "bite-sized" learning capsules ensure that your review of any given topic is quick, efficient, and comprehensive, allowing you to target the exact information you need for classroom and exam success.

New features of this bestselling review book:

Increased focus on pathobiochemical aspects and clinical correlations, especially useful for exam preparation in the clinical sciences
New and expanded sections on the immune and digestive systems, motor proteins, transport processes, blood clotting and fibrinolysis, biochemistry of fatty tissue, metabolic integration, neurotransmitters and their receptors, signal transduction, and much more!
Symbols for atoms, biomolecules, coenzymes, biochemical processes, and chemical reactions are color-coded to promote quick comprehension
Computer graphics that provide simulated 3D representations of important molecules, making complex subject matter tangible
Convenient color thumb index that guides you quickly through the book
This superb didactic atlas has been used by medical and health science students worldwide since its first publication in German in 1994 and has since been translated into fifteen languages. Its unrivalled illustrations, concise text, and focused presentation all combine to create an excellent, high-yield study guide.''',
      link:
          'http://93.174.95.29/main/0/a65e99098267988bb59ff8055b609aec/%28Flexibooks%29%20Jan%20Koolman%2C%20K.%20Rohm%20-%20Color%20Atlas%20of%20Biochemistry-Thieme%20%282005%29.pdf'),
  Book(
      id: 95,
      subject: 'Biochemistry',
      title: 'Medical Biochemistry: The Big Picture',
      writer: 'Lee W. Janson  (Author), Marc Tischler (Author)',
      edition: '1ST',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51iR8MIpGIL._SX386_BO1,204,203,200_.jpg',
      rating: 3.2,
      description:
          '''Get the BIG PICTURE of Medical Biochemistry – and target what you really need to know to ace the course exams and the USMLE Step 1

300 FULL-COLOR ILLUSTRATIONS

Medical Biochemistry: The Big Picture is a unique biochemistry review that focuses on the medically applicable concepts and techniques that form the underpinnings of the diagnosis, prognosis, and treatment of medical conditions. Those preparing for the USMLE, residents, as well as clinicians who desire a better understanding of the biochemistry behind a particular pathology will find this book to be an essential reference. Featuring succinct, to-the-point text, more than 300 full-color illustrations, and a variety of learning aids, Medical Biochemistry: The Big Picture is designed to make complex concepts understandable in the shortest amount of time possible.

This full-color combination text and atlas features:

Progressive chapters that allow you to build upon what you’ve learned in a logical, effective manner
Chapter Overviews that orient you to the important concepts covered in that chapter
Numerous tables and illustrations that clarify and encapsulate the text
Sidebars covering a particular disease or treatment add clinical relevance to topic discussed
Essay-type review questions at the end of each chapter allow you to assess your comprehension of the major topics
USMLE-style review questions at the end of each section
Three appendices, including examples of biochemically based diseases, a review of basic biochemical techniques, and a review of organic chemistry/biochemistry''',
      link:
          'https://drive.google.com/uc?export=download&id=1TSZXsRnDSsQYm2kL9jXQY_cVrsfFzugc'),
  Book(
      id: 96,
      subject: 'Biochemistry',
      title: 'Integrative medical biochemistry : examination and board review',
      writer: 'Michael W. King  (Author)',
      edition: '1ST',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/519k0%2BWejWL._SX388_BO1,204,203,200_.jpg',
      rating: 4.5,
      description: '''Essential for USMLE Step 1 review!
A rigorous full-color review for any type of biochemistry or medical biochemistry examination!

Integrative Medical Biochemistry Examination and Board Review is a fast and effective way for you to prepare for regular course examinations in biochemistry and medical biochemistry, as well as medical board exams and the USMLE Step 1. A unique feature of this review is the integration of medical biochemistry with physiology, pathophysiology, pathology, and anatomy, making it perfect for today\'s rapidly changing medical school curriculum. Integrative Medical Biochemistry Examination and Board Review is logically divided into four sections:

Section 1 covers the basics of the major building blocks of all cells and tissues
Section 2 discusses metabolic biochemistry with a strong emphasis on clinical correlations and clinical disorders related to these all important pathways
Section 2 reviews the Cellular and Molecular Biology topics associated with medical biochemistry, physiology, and pathology
Section 4 includes 10 chapters with high-yield integrative topics of value not only to medical students, but to all students of the discipline
Packed with valuable learning aids:

1,100 multiple-choice questions, half of which are USMLE Step 1 style
Thorough explanations for each answer
350 full-color illustrations
Every chapter includes:
An outline listing the major topics covered
A list of high-yield terms related to the content
Numerous explanatory figures and tables designed to increase your understanding of must-know material
A checklist that recaps important and high-yield concepts
Most chapters include detailed clinical boxes that present high-yield information concerning diseases and disorders related to defects in the pathways being discussed''',
      link:
          'https://drive.google.com/uc?export=download&id=1pwWHtd2jOX4j_Ih4pEFoG_D9UYWhzLh7'),
  Book(
      id: 97,
      subject: 'Biochemistry',
      title:
          'The Physical Basis of Biochemistry: The Foundations of Molecular Biophysics',
      writer: 'Peter R. Bergethon (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41gPXP%2BjW4L._SX313_BO1,204,203,200_.jpg',
      rating: 1.0,
      description:
          '''Biological chemistry has changed since the completion of the human genome project. There is a renewed interest and market for individuals trained in biophysical chemistry and molecular biophysics. The Physical Basis of Biochemistry, Second Edition, emphasizes the interdisciplinary nature of biophysical chemistry by incorporating the quantitative perspective of the physical sciences without sacrificing the complexity and diversity of the biological systems, applies physical and chemical principles to the understanding of the biology of cells and explores the explosive developments in the area of genomics, and in turn, proteomics, bioinformatics, and computational and visualization technologies that have occurred in the past seven years. The book features problem sets and examples, clear illustrations, and extensive appendixes that provide additional information on related topics in mathematics, physics and chemistry.''',
      link:
          'https://drive.google.com/uc?export=download&id=1TDbC6nsEdxk83gj7Aju3JxfS4IGcXeWI'),
  Book(
      id: 98,
      subject: 'Biochemistry',
      title: 'Practical Textbook of Biochemistry for Medical Students',
      writer: 'D. M. Vasudevan (Author), Subir Kumar Das (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/516QOaVTThL._SX381_BO1,204,203,200_.jpg',
      rating: 1.0,
      description:
          '''2nd Edition. - Jaypee Brothers Medical Publishers, 2013. - 161 p. - The book Practical Textbook of BIOCHEMISTRY for Medical Students is a practical guide wherein it includes the qualitative and quantitative experiments, which the medical students are supposed to do by themselves in practical classes. The book is divided into three parts. Part A deals with qualitative experiments, wherein the authors have discussed about tests for proteins, carbohydrates; analysis of urea, uric acid, vitamin A, vitamin C, milk, bile and urine. Part B deals with quantitative experiments, wherein the discussion on estimation of components (chlorides, ammonia and glucose) in urine; sugar, urea, creatinine, uric acid, haemoglobin, Albumin/globulin ratio, calcium, inorganic phosphate, cholesterol, bilirubin, amylase, alkaline phosphatase and transaminase activity in blood serum is made. The book also gives out some more experiments (Part C), which may not be possible for the students to do by themselves. Few of the experiments will be demonstrated in the practical classes. In the end, a few case reports are also included, which will be useful for the student to prepare for the practical examinations. On the whole this practical book is friendly to the students and useful to the teachers.''',
      link:
          'https://drive.google.com/uc?export=download&id=1QMRS9kgRF3URbf0Np1zlntXayFdXuVNt'),
  Book(
      id: 99,
      subject: 'Biochemistry',
      title: 'Clinical Biochemistry:Metabolic and Clinical Aspects',
      writer:
          'Marshall MA PhD MSc MBBS FRCP FRCPath FRCPEdin FRSB FRSC, William J. (Author), Lapsley MB BCh BAO MD FRCPath, Márta (Author), Day MA MSc MBBS FRCPath, Andrew (Author), Ayling PhD FRCP FRCPath, Ruth (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51EXKfZh9aL._SX389_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''Now fully revised and updated, Clinical Biochemistry, third edition is essential reading for specialty trainees, particularly those preparing for postgraduate examinations. It is also an invaluable current reference for all established practitioners, including both medical and scientist clinical biochemists.

Building on the success of previous editions, this leading textbook primarily focuses on clinical aspects of the subject, giving detailed coverage of all conditions where clinical biochemistry is used in diagnosis and management – including nutritional disorders, diabetes, inherited metabolic disease, metabolic bone disease, renal calculi and dyslipidaemias. The acquisition and interpretation of clinical biochemical data are also discussed in detail.

Expanded sections on haematology and immunology for clinical biochemists provide a thorough understanding of both laboratory and clinical aspects
New chapters are included on important evolving areas such as the metabolic response to stress, forensic aspects of clinical biochemistry and data quality management
An extended editorial team - including three expert new additions – ensures accuracy of information and relevance to current curricula and clinical practice
A superb new accompanying electronic version provides an enhanced learning experience and rapid reference anytime, anywhere!
Elsevier ExpertConsult.com

Enhanced eBooks for medical professionals

Compatible with PC, Mac®, most mobile devices and eReaders, browse, search, and interact with this title – online and offline. Redeem your PIN at expertconsult.com today!

Straightforward navigation and search across all Elsevier titles
Seamless, real-time integration between devices
Adjustable text size and brightness
Notes and highlights sharing with other users through social media
Interactive content''',
      link:
          'http://93.174.95.29/main/1321000/43f538fe8a93fc9553e91a92761531fb/William%20J.%20Marshall%2C%20M%C3%A1rta%20Lapsley%2C%20Andrew%20Day%2C%20Ruth%20Ayling%20-%20Clinical%20Biochemistry%20_%20Metabolic%20and%20Clinical%20Aspects-Elsevier%20%282014%29.pdf'),
  Book(
      id: 100,
      subject: 'Biochemistry',
      title: 'Essentials of Biochemistry (for Medical Students)',
      writer: 'Shivananda Nayak B (Author)',
      edition: '2ND',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51rN1hbi1rL._SX371_BO1,204,203,200_.jpg',
      rating: 1.0,
      description:
          '''The second edition ofEssentials of Biochemistryhas been fully updated to provide medical students with a thorough understanding of the fundamentals of biochemistry.

This comprehensive manual covers a multitude of topics within biochemistry, with chapters dedicated to specific diseases such as AIDS and cancer.

Each chapter begins with an introductory abstract and keywords, and ends with multiple choice questions and answers to assist learning and revision.


Key points

Thoroughly revised, new edition providing medical students with fundamentals of biochemistry
Each chapter includes multiple choice questions and answers for revision
Presents 290 images, illustrations, tables and flow charts
Previous edition published in 2008''',
      link:
          'https://drive.google.com/uc?export=download&id=1xTqiYGsVHsjh7bg3XxAX0EIhgVxQQ_Ui'),
  Book(
      id: 101,
      subject: 'Biochemistry',
      title: 'Lehninger Principles of Biochemistry',
      writer: 'Albert Lehninger, David L. Nelson, Michael M. Cox',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/610yw2FxTeL._SX390_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''"Clear writing and illustrations…Clear explanations of difficult concepts…Clear communication of the ways in biochemistry is currently understood and practiced. For over 35 years, in edition after bestselling edition, Principles of Biochemistry has put those defining principles into practice, guiding students through a coherent introduction to the essentials of biochemistry without overwhelming them.

The new edition brings this remarkable text into a new era. Like its predecessors, Lehninger Principles of Biochemistry, Sixth Edition strikes a careful balance of current science and enduring concepts, incorporating a tremendous amount of new findings, but only those that help illustrate biochemistry’s foundational principles. With this edition, students will encounter new information emerging from high throughput DNA sequencing, x-ray crystallography, and the manipulation of genes and gene expression, and other techniques. In addition, students will see how contemporary biochemistry has shifted away from exploring metabolic pathways in isolation to focusing on interactions among pathways. They will also get an updated understanding of the relevance of biochemistry to the study of human disease (especially diabetes) as well as the important role of evolutionary theory in biochemical research.

These extensive content changes, as well as new art and powerful new learning technologies make this edition of Lehninger Principles of Biochemistry the most impressive yet."''',
      link:
          'https://drive.google.com/uc?export=download&id=111pxcT9Z3YjPZlb2CIgwtxInY4YDGClA'),
  Book(
      id: 102,
      subject: 'Biochemistry',
      title: 'MCQs in Biochemistry',
      writer: 'G. Vidya Sagar (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/511bqw0eHuL._SX373_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1Is_MZLy76gxYjGM4qUZ4jYMB3GV5h3sS'),
  Book(
      id: 103,
      subject: 'Biochemistry',
      title: 'Self assessment and review of biochemistry',
      writer: 'Rebecca James Perumcheril(Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51VLMbx1bfL._SX376_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''The bestselling biochemistry book with questions up to January 2019. Fully colored book based on the latest examination pattern. 99% of 2018-19 PGMEE questions came from this book. Written by the best faculty of biochemistry in PG training programs. Synopsis of each topic given in bulleted format. A section of full color image-based questions given in the beginning with explanatory Answers. Image-based information provided in boxes within chapters for better clarity. New: based on facts and concepts from Harrison 20/e, Nelson 20/e, Lehninger 7/e, Harper 31/e, Lippincott 7/e, Emery 15/e, teitz 7/e, Devlin 8/e, and CMDT 2019. New: all chapters have been divided into sub-chapters and review questions (MCQs), their answers, explanations and references given after all sub-chapters to avoid boredom in reading big theory chapters. New: quick one-liners and check list for easy revision provided at the end of each sub-br>chapter new: recent questions of 2018-19 are highlighted. New: loaded with more conceptual diagrams, flowcharts, mnemonics and tables for easy learning. New: depicts metabolic disorders at a Glance with diagram. New: concept boxes added for better understanding. High-yield points provided in boxes for last minute revision in every sub-br>chapter contains symptom boxes to give clinical understanding of the disorders. New: the content and sequence of the book is in accordance with online cme in daily rounds and marrow app. Includes all recent model questions (2019-2000), AIIMS (Nov 2018-2000), AIPGMEE (2012-2000), PGI (Nov 2018-2000), JIPMER (2018-2000) and various State and deemed University exams. Online author support for learning and clarifications. Highly recommended by Toppers of all PGMEEs. Must-learn book for all the PG entrance examinations.''',
      link:
          'http://93.174.95.29/main/2237000/8553296cb97631de6a8bd7f3fc1a1c72/Rebecca%20James%20Perumcheril%20-%20Self%20assessment%20and%20review%20of%20biochemistry-Jaypee%20Brothers%20Medical%20Publishers%20%282017%29.pdf'),
  Book(
      id: 104,
      subject: 'MicroBiology',
      title: 'Lippincott Illustrated Reviews: Microbiology',
      writer:
          'Richard A. Harvey PhD (Author), Cynthia Nau Cornelissen Ph.D. (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41rVeFVKYxL._SX385_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''A MUST READ for mastering essential concepts in microbiology
Well-known and widely used for their hallmark illustrations, Lippincott’s Illustrated Reviews bring concepts to vibrant life. Students rely on LIR for quick review, easier assimilation, and understanding of large amounts of critical, complex material.
• Outline format and full-color illustrations: More than 400 color illustrations and color-coded summaries provide key information at a glance and helpful visual explanations
• Illustrated case studies and questions to support USMLE prep: Expanded discussions reinforce key concepts and review questions with detailed rationales allow for self-assessment
• New bookmark features mini-index of important microorganisms for quick and easy reference
"Microbiology can be an overwhelming topic, but the pictures, concise descriptions, and parallel structure of each chapter helps to make the subject easier to understand and digest.” – Amelia Keaton, medical student
"I think this book better meets the needs of the market because of its review chapters and disease summaries, its review questions, and its excellent photographs of clinical manifestations of microbial disease. I also found this book easier to read and study from.” – Devorah Segal, medical student
FREE online! (with purchase of the text)
• Interactive question bank for test-taking practice
• Fully searchable eBook for studying on-the-go''',
      link:
          'https://drive.google.com/uc?export=download&id=1YFYrKpch38hcEPYj-CSxnoA8afMUGUas'),
  Book(
      id: 105,
      subject: 'MicroBiology',
      title: 'Basic medical microbiology',
      writer: 'Patrick R.Murray',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51AqmoRAyoL._SX403_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''Authored by the lead author of the bestselling Medical Microbiology and written in the same tradition, Basic Medical Microbiology was designed as a straight-forward, practical introduction to this difficult topic. It provides students with a firm foundation in the principles and applications of microbiology, serving as an effective prep tool for examinations and the transition into clinical application.

Carefully curated contents focus on the most commonly observed and tested organisms and diseases.
Differential diagnosis, organism classification overview, and a list of antimicrobials used to treat infections are provided in the introductory chapter of each organism section, reinforcing the clinical application and relevance.
Organized by organism; focuses on the association between an organism and disease.
Concise tables and high-quality illustrations offer visual guidance and an easy review of key material.
Clinical cases reinforce the clinical significance of each organism.
Includes multiple-choice questions to aid in self-assessment and examination preparation.
Evolve Instructor Resources, including a downloadable image bank, are available to instructors through their Elsevier sales rep or via request at: https://evolve.elsevier.com
Student Consult eBook version included with purchase. This enhanced eBook experience allows you to search all of the text, figures, images, and references from the book on a variety of devices.''',
      link:
          'https://drive.google.com/uc?export=download&id=1rKQQp03-8F8oBYZRosN3upEQVlheEQrf'),
  Book(
      id: 106,
      subject: 'MicroBiology',
      title: 'Jawetz, Melnick, & Adelberg’s Medical Microbiology',
      writer:
          'Karen C. Carroll, Jeffery A. Hobden, Steve Miller, Stephen A. Morse, Timothy A. Mietzner, Barbara Detrick, Thomas G. Mitchell, James H. McKerrow, Judy A. Sakanari',
      edition: '27th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51kRnd8WLDL._SX389_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''The twenty-seventh edition of Jawetz, Melnick & Adelberg’s Medical Microbiology delivers a concise, up-to-date overview of the roles microorganisms play in human health and illness. Linking fundamental principles with the diagnosis and treatment of microbial infections, this classic text has been updated throughout to reflect the tremendous expansion of medical knowledge afforded by molecular mechanisms, advances in our understanding of microbial pathogenesis, and the discovery of novel pathogens.

Along with brief descriptions of each organism, you will find vital perspectives on pathogenesis, diagnostic laboratory tests, clinical findings, treatment, and epidemiology. The book also includes an entire chapter of case studies that focuses on differential diagnosis and management of microbial infections.''',
      link:
          'https://drive.google.com/uc?export=download&id=10BfmTnfGxAn3KUNul90omARgCSK4Nh18'),
  Book(
      id: 107,
      subject: 'MicroBiology',
      title: 'Review of Medical Microbiology and Immunology',
      writer: 'Warren E. Levinson',
      edition: '6th',
      image:
          'http://medicalbooksfree.com/wp-content/uploads/2018/08/Review-of-Microbiology-and-Immunology-6th-edition.jpg',
      rating: 3.9,
      description:
          '''• The only MCQ book in any subject written by textbook authors.

• Thoroughly revised, updated and fully colored edition.

• All image based microbiology MCQs of 2016 came from this book.

• Facts and concepts have been taken from latest editions of Harrison (19th), Park (23rd), Jawetz (25th), Apurba Sastry’s Essentials of Medical Microbiology, Apurba Sastry’s Essentials of Medical Parasitology and Ananthanarayan (9th edition).

• Latest updates included such as BMW Rule 2016, Zika, H1N1, Ebola virus, Polio eradication, Vaccine-derived PolioVirus (VDPV), MERS CoV, etc.

• Includes questions along with explanatory answers of AIIMS (2000-2016 Nov), PGI (2000-2016 Nov), JIPMER (2009-2016 Nov), All India (2000-2012), DNB (2000-2012) and recent questions from other national level examinations (2013-2016).

• Contains recent MCQs from state entrance exams such as APPG (2000-2016), TNPG (2009-2016), MHPG (2009-2016), West Bengal PG (2012-2016), COMEDK (2013-2016), CMC Vellore 2016 and latest MCQs from other national and state entrances.''',
      link:
          'https://drive.google.com/uc?export=download&id=1sAQxux1nd24UD1xHZQ1rRQvtpm46R1hh'),
  Book(
      id: 108,
      subject: 'MicroBiology',
      title: 'Principles of Microbiology',
      writer: 'M. S. Bhatia',
      edition: '1st',
      image:
          'https://b-ok.cc/covers/books/6c/77/8b/6c778b99d050c3444c08d9a0f9afa6e6.jpg',
      rating: 2.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1eBRChdrLeticxXmSkDw54uR3rcx6sD-k'),
  Book(
      id: 109,
      subject: 'MicroBiology',
      title: 'Textbook Of Microbiology',
      writer: 'R. Ananthanarayan and C.K. Jayaram Paniker',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/31LYTlew9TL._BO1,204,203,200_.jpg',
      rating: 2.0,
      description: '''Publisher: Universities Pr. (2008)
Language: English
ISBN-10: 8173716323
ISBN-13: 978-8173716324''',
      link:
          'http://93.174.95.29/main/1508000/f914c988c773cf0a0fe68134ab61f592/R.%20Ananthanarayan%20and%20C.K.%20Jayaram%20Paniker%20-%20Ananthanarayan%20and%20Paniker%E2%80%99s%20Textbook%20of%20Microbiology.pdf'),
  Book(
      id: 110,
      subject: 'MicroBiology',
      title: 'Mims Medical Microbiology and Immunology',
      writer: 'Richard Goering, Hazel Dockrell, Mark Zuckerman, Peter Chiodini',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51XwUY5uL%2BL._SX389_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''Learn all the microbiology and basic immunology concepts you need to know for your courses and exams. Now fully revised and updated, Mims’ clinically relevant, systems-based approach and abundant colour illustrations make this complex subject easy to understand and remember.''',
      link:
          'https://drive.google.com/uc?export=download&id=1guazkNQ2qgT1SjT7AmfJyEkRqQQ08OdM'),
  Book(
      id: 111,
      subject: 'MicroBiology',
      title: 'Microbiology. A Laboratory Manual',
      writer: 'Cappuccino James, Sherman Natalie',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51HqM9h6jiL._SX388_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''Versatile, comprehensive, and clearly written, this competitively priced laboratory manual can be used with any undergraduate microbiology text—and now features brief clinical applications for each experiment, and a new experiment on hand washing. Microbiology: A Laboratory Manual is known for its thorough coverage, descriptive and straightforward procedures, and minimal equipment requirements. A broad range of experiments helps to convey basic principles and techniques. Each experiment includes an overview, an in-depth discussion of the principle involved, easy-to-follow procedures, and lab reports with review and critical thinking questions. Ample introductory material and laboratory safety instructions are provided.''',
      link:
          'https://drive.google.com/uc?export=download&id=17sxzYrS1D4YV5BmyeI19SwdtwVMdHfOC'),
  Book(
      id: 112,
      subject: 'MicroBiology',
      title: 'Microbiology: A Systems Approach',
      writer: 'Marjorie Kelly Cowan (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41CZPxEjTAL._SX403_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''Microbiology: A Systems Approach is a microbiology text for non-science/allied health majors with a body systems approach to the disease chapters. It has become known for its engaging writing style, instructional art program and focus on active learning. We are so excited to offer a robust learning program with student-focused learning activities, allowing the student to manage their learning while you easily manage their assessment. Detailed reports show how your assignments measure various learning objectives from the book (or input your own!), levels of Bloom\'s Taxonomy or other categories, and how your students are doing. The Cowan Learning program will save you time and improve your students\' success in this course.
Users who purchase Connect Plus receive access to the full online ebook version of the textbook.''',
      link:
          'https://drive.google.com/uc?export=download&id=1lUeSS1NypBO2l7xiJRacWclg-Zkf1Pla'),
  Book(
      id: 113,
      subject: 'MicroBiology',
      title: 'Prescott’s Microbiology',
      writer:
          'Joanne Willey (Author), Linda Sherwood (Author), Christopher J. Woolverton (Author)',
      edition: '10th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51BS1y-uylL._SX410_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''The author team of Prescott\'s Microbiology continues the tradition of past editions by providing a balanced, comprehensive introduction to all major areas of microbiology. Because of this balance, Microbiology is appropriate for microbiology majors and mixed majors courses. The new authors have focused on readability, artwork, and the integration of several key themes (including evolution, ecology and diversity) throughout the text, making an already superior text even better.
Users who purchase Connect Plus receive access to the full online ebook version of the textbook.''',
      link:
          'https://drive.google.com/uc?export=download&id=15Xwex9P9w2I7miWTpPL4c107ibfT4xSk'),
  Book(
      id: 114,
      subject: 'MicroBiology',
      title: 'Essentials of  MEDICAL MICROBIOLOGY',
      writer: 'Apurba S. Sastry (Author), Sandhya Bhat (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/61V9rrZEQuL._SX367_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''More content, less pages-handy look, saves a student’s time
Concise, bulleted format and to-the-point text-easy to read during examination
Simple and lucid language makes the understanding easy
Separate boxes for summary of laboratory diagnosis and treatment-for quick review
Clinical case-based essay questions and MCQs incorporated at the end of the chapter-to reinforce the students to prepare for future exams.''',
      link:
          'https://drive.google.com/uc?export=download&id=1zKn166jdBm0erf4YdYuHGqTFctMgB45r'),
  Book(
      id: 115,
      subject: 'MicroBiology',
      title: 'Microbiology in Clinical Practice',
      writer: 'D. C. Shanson  (Author)',
      edition: '2nd',
      image:
          'https://images-eu.ssl-images-amazon.com/images/I/51VjrL%2BLnJL.jpg',
      rating: 3.9,
      description:
          '''Microbiology in Clinical Practice presents the infections and syndromes caused by micro-organisms. It discusses the management of infective diseases and aetiological agents. It addresses the latex agglutination, immunofluorescent, monoclonal antibody, and nucleic acid probe investigations.
Some of the topics covered in the book are the classification and pathogenicity of microbes; classification of bacteria; classification of viruses; classification of fungi; general principles of antimicrobial chemotherapy; antibiotic sensitivity tests; procedures in the laboratory for microbiological diagnosis; and the mode of action of antimicrobial drugs. The resistance to antimicrobial drugs are covered. The microbiological investigations of septicaemia are discussed. The text describes the human immunodeficiency virus infection and AIDS in infants. A study of the congenital immunodeficiency and impaired resistance to infection is presented. A chapter is devoted to the predisposing factors for anaerobic infections. Another section focuses on the infections of the central nervous system.
The book can provide useful information to doctors, pathologists, neurologists, students, and researchers.''',
      link:
          'https://drive.google.com/uc?export=download&id=1PyT8hCQJTtiS0XxjsurvPhnF05j6UIci'),
  Book(
      id: 116,
      subject: 'MicroBiology',
      title: 'Elsevier\'s Medical Laboratory Science Examination Review',
      writer:
          'Linda Graeter (Author), Elizabeth Hertenstein (Author), Charity Accurso (Author), Gideon Labiner  (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/514c7FIsxsL._SX388_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''Elsevier\'s Medical Laboratory Science Examination Review is a brand-new resource that offers all the review, practice, and support you need to prepare for the either the MLS or MLT certification examination. Each chapter in the book offers a thorough review on one of the core areas of Medical Laboratory Science as outlined by the ASCP Board of Certification. Practice questions are also featured at the end of each chapter and explanations and rationales for each correct answer appear at the end of the text. Plus, an eight-page full-color insert displays photomicrographs of hematological and microbiological specimens exactly as they appear under the microscope and on the MLS and MLT certification exams. A mock certifications exam is included in the print book as well as online at the companion Evolve website – which also houses additional practice questions – totaling 1,000 questions in all.

Inclusion of both MLS and MLT level content and questions enables the book to be used for both certification exams
Print mock exam at the end of the book contains 100 certification examination preparation questions.
Content reviews in outline form enables each topic to be easily reviewed but covered in an appropriate depth.
Online mock exams on the companion Evolve website include all the practice questions from the book plus additional unique questions that can be used to create mock exams for extra practice.
Eight-page full-color insert within the book features 50 illustrations that show hematological and microbiological photomicrographs.
Test-taking tips and suggestions discuss the exam, how it’s set up and scored, when to answer, guess and not answers questions, how to identify distracters, and more.''',
      link:
          'https://drive.google.com/uc?export=download&id=17iN8ZRWLTZj6HTd4_LwhYNlR7NoRpaMa'),
  Book(
      id: 117,
      subject: 'MicroBiology',
      title: 'Medical Laboratory Science Review',
      writer: 'Harr MS MLS (ASCP), Robert R. (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/5147C5vEwmL._SX384_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''Multiple-choice questions provide test-item classifications that categorize each question by subject category, task, and taxonomy level.

Detailed rationales explain why each answer is correct or incorrect.

Hemostasis content explores thrombophilias and anticoagulant therapy.

The most recent coverage of tumor markers includes new FDA-approved tests.

An overview of basic molecular diagnostic principles with thorough explanations offer an introduction to the field.

Problem-solving sections in each chapter reinforce the practical application of material.''',
      link:
          'http://93.174.95.29/main/1201000/4246597ccbd94058d27c9ca667029ecd/Robert%20R.%20Harr%20MS%20MLS%20%28ASCP%29%20-%20Medical%20Laboratory%20Science%20Review-F.A.%20Davis%20Company%20%282012%29.pdf'),
  Book(
      id: 118,
      subject: 'MicroBiology',
      title: 'Quick Review Cards for Medical Laboratory Science',
      writer: 'Valerie Dietz Polansky  (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51RPdHjW8DL._SX331_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Covers the essentials of seven major disciplines covered on the MLS and MLT examinations • general lab practice • hematology • immunology/serology • immunohematology • clinical chemistry • body fluids • clinical microbiology • management and education.

Quick and efficient way to review for class and certification exams.''',
      link:
          'https://drive.google.com/uc?export=download&id=1wsG-L9iBD0h9_27PORkcIvfbdzrlv8ec'),
  Book(
      id: 119,
      subject: 'MicroBiology',
      title: 'MCQs in Microbiology',
      writer: 'G. Vidya Sagar (Author))',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41NOGr7xFIL._SX363_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1foo4HIihR0fATdhn2HTUyO8ZjePy8sEh'),
  Book(
      id: 120,
      subject: 'Community Medicine',
      title: 'k.park-park\'s textbook of preventive and social medicine',
      writer: 'by K Park (Author)',
      edition: '24rd Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41Mk6omCDzL._SX322_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''The The book is must read for community medicine in the third year since it is the most widely used book by MBBS students. The Epidemiology, Screening for disease, Epidemiology of communicable diseases and chronic non-communicable diseases are usually focused in the end. The free book has over 942 pages with pretty clean pages and nice illustrations with flowcharts and boxes. K Park free book features 22 Chapters in total with an abbreviations and index at the end.''',
      link:
          'https://drive.google.com/uc?export=download&id=1T5tUKHkNsstf4Q4RPhv6URT16QAEVElF'),
  Book(
      id: 121,
      subject: 'Community Medicine',
      title: 'Mahajan and Gupta Textbook of Preventive and Social Medicine',
      writer: 'Roy R. N.',
      edition: '4TH Edition',
      image:
          'https://b2n5k8x3.stackpathcdn.com/assets/thumbs/7fc/7fc5bda431a266c1c6fea0b9f4f1d9b9.jpg',
      rating: 4.3,
      description:
          '''Mahajan & Gupta Textbook of Preventive and Social Medicine 4th Edition is a comprehensive book for students specializing in Community Medicine. The book is useful for postgraduate students, and comprises of several flow charts, diagrams and pictures which have been introduced for the purpose of clarity. It will benefit students by preparing them for the MCQs in the postgraduate examinations.''',
      link:
          'https://drive.google.com/uc?export=download&id=1zNS85Hriaw3jKYGGmq3uO2ZdmJVVpZ3u'),
  Book(
      id: 122,
      subject: 'Community Medicine',
      title: 'Monicas District Labs in Tropical Countries Part 1',
      writer: 'Monica Cheesbrough,Cheesbrough Monica',
      edition: '2nd Edition',
      image:
          'https://rukminim1.flixcart.com/image/832/832/book/3/0/4/district-laboratory-practice-in-tropical-countries-part-1-2nd-original-imaeas764zg5fqhh.jpeg',
      rating: 4.0,
      description:
          '''This new edition includes an update on HIV disease/AIDS, recently developed HIV rapid tests to diagnose HIV infection and screen donor blood, and current information on antiretroviral drugs and the laboratory monitoring of antiretroviral therapy. Information on the epidemiology and laboratory investigation of other pathogens has also been brought up to date. Several new, rapid, simple to perform immunochromatographic tests to assist in the diagnosis of infectious diseases are described, including those for brucellosis, cholera, dengue, leptospirosis, syphilis and hepatitis. Recently developed lgM antibody tests to investigate typhoid fever are also described. The new classification of salmonellae has been introduced. Details of manufacturers and suppliers now include website information and e-mail addresses. The haematology and blood transfusion chapters have been updated, including a review of haemoglobin measurement methods in consideration of the high prevalence of anaemia in developing countries.''',
      link:
          'https://drive.google.com/uc?export=download&id=1ln4NwlvQlea4dPgOejwc7Hfj5FTaDJPx'),
  Book(
      id: 123,
      subject: 'Community Medicine',
      title: 'Monicas District Labs in Tropical Countries Part 2',
      writer: 'Monica Cheesbrough,Cheesbrough Monica',
      edition: '2nd Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41CDplzd2kL._SX382_BO1,204,203,200_.jpg',
      rating: 4.0,
      description:
          '''This new edition includes an update on HIV disease/AIDS, recently developed HIV rapid tests to diagnose HIV infection and screen donor blood, and current information on antiretroviral drugs and the laboratory monitoring of antiretroviral therapy. Information on the epidemiology and laboratory investigation of other pathogens has also been brought up to date. Several new, rapid, simple to perform immunochromatographic tests to assist in the diagnosis of infectious diseases are described, including those for brucellosis, cholera, dengue, leptospirosis, syphilis and hepatitis. Recently developed lgM antibody tests to investigate typhoid fever are also described. The new classification of salmonellae has been introduced. Details of manufacturers and suppliers now include website information and e-mail addresses. The haematology and blood transfusion chapters have been updated, including a review of haemoglobin measurement methods in consideration of the high prevalence of anaemia in developing countries.''',
      link:
          'https://drive.google.com/uc?export=download&id=1ln4NwlvQlea4dPgOejwc7Hfj5FTaDJPx'),
  Book(
      id: 124,
      subject: 'Community Medicine',
      title: 'Clinical Communication in Medicine',
      writer:
          'Jo Brown  (Editor), Lorraine Noble (Editor), Alexia Papageorgiou (Editor), Jane Kidd (Editor)',
      edition: '1st Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41caUFhnn4L._SX331_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''Highly Commended at the British Medical Association Book Awards 2016 Clinical Communication in Medicine brings together the theories, models and evidence that underpin effective healthcare communication in one accessible volume. Endorsed and developed by members of the UK Council of Clinical Communication in Undergraduate Medical Education, it traces the subject to its primary disciplinary origins, looking at how it is practised, taught and learned today, as well as considering future directions. Focusing on three key areas the doctor-patient relationship, core components of clinical communication, and effective teaching and assessment Clinical Communication in Medicine enhances the understanding of effective communication. It links theory to teaching, so principles and practice are clearly understood. Clinical Communication in Medicine is a new and definitive guide for professionals involved in the education of medical undergraduate students and postgraduate trainees, as well as experienced and junior clinicians, researchers, teachers, students, and policy makers.''',
      link:
          'https://drive.google.com/uc?export=download&id=1c9VeA1wZTHLN9oU7VGoNtnrbbKv-6B5m'),
  Book(
      id: 125,
      subject: 'Community Medicine',
      title: 'Community Medicine: A Student Manual',
      writer: 'Parikshit Sanyal (Author)',
      edition: '1st Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41FjE4cC1eL._SX310_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''Community medicine is the application of medical science to the society at large. It covers such diverse areas ranging from vaccination and control of epidemics to sanitation and town planning. This textbook is an attempt to present the subject of community medicine at a most introductory level to undergraduate medical students. It provides solid conceptual foundation of biostatistics. Major areas of community medicine including communicable and noncommunicable diseases, environmental health, mother and child’s health, immunization, nutrition and national health programs are covered extensively. However, care has been taken as not to burden the memory of the student with irrelevant details at any point. Regarding style, the book shapes into an easy-to-learn format. Important definitions presented in an information and simple manner emphasizing on keywords. Consistent use of highlight boxes improve the readability of the text and underline key facts. It is written in a manner akin to class notes, with a basic framework which every student can follow, while also providing additional material for the interesting areas. The book is enriched with only the latest facts, figures and guidelines from international (WHO, CIA, UNICEF, etc.) and national (Ministry of Health and Family Welfare) agencies. Website references to topics, online libraries and sources of reliable information are provided in the references to each chapter. Profusely illustrated both by original and public domain artwork and imagery, it is also a very pleasant read.''',
      link:
          'https://drive.google.com/uc?export=download&id=1JCnlkw2qJK4GDv72ZkOxoHr2yUTFvoZc'),
  Book(
      id: 126,
      subject: 'Community Medicine',
      title:
          'Essential Community Medicine: (including Relevant Social Services)',
      writer: 'R.J. Donaldson (Editor)',
      edition: 'Paperback – 25 February 2012',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41JxtKdB1SL._SX322_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''This basic textbook of Community Medicine, which includes descriptions of the related social ~ervices, is intended for a wide range of readers who require knowledge and understanding of the essential aspects of the subject. These include undergraduate medical students and qualified doctors who are engaged in postgraduate courses of study or training schemes, particularly those in community medicine and general practice. When writing this book we also had in mi nd the needs of students of nursing at all levels at a time when an increasing emphasis on the community is being reflected in the content of curricula and the composition of examination papers. It is our view that this account of community medicine will also be of value to established practitioners -community physicians, community health doctors, senior nurses and health visitors - who wish to con- solidate or update their knowledge. The growing involvement of the professions in the management and planning of health services means that many general practitioners, hospital doctors and nurses are being called upon to take a population perspective and to become acquainted with many of the concepts and issues discussed in this book. In addition, there are those professionals who work closely with medicine and nursing and have a common concern in providing care and promoting prevention -groups such as social workers and health education personnel. For all these reasons we would ho pe that many groups might read the book and find it useful.''',
      link:
          'https://drive.google.com/uc?export=download&id=1QKKRCtEje2y5qoUS49odX3kl81lIczoO'),
  Book(
      id: 127,
      subject: 'Internal Medicine',
      title: 'MACLEOD’S CLINICAL EXAMINATION',
      writer: '',
      edition: '14th',
      image:
          'https://www.medgag.com/wp-content/uploads/2018/03/Screenshot-19-746x1024.png',
      rating: 4.5,
      description:
          '''This classic textbook aims to assist clinicians develop the consultation skills required to elicit a clear history, and the practical skills needed to detect clinical signs of disease. Where possible, the physical basis of clinical signs is explained to aid understanding. Formulation of a differential diagnosis from the information gained is introduced, and the logical initial investigations are included for each system.

Key Features
The first part of the book addresses the general principles of good interaction with patients, from the basics of taking a history and examining, to the use of pattern recognition to identify spot diagnoses.
The second part documents the relevant history, examination and investigations for all the major body systems.
The third part illustrates the application of these skills to specific clinical situations.
The final part covers preparation for assessments of clinical skills and the use of these skills in everyday practice.''',
      link:
          'http://93.174.95.29/main/2339000/8a69a7c0120ccfa066e6cc7bb7c62597/%28E%C4%9Fitim%20Tanr%C4%B1s%C4%B1%29%20J.%20Alastair%20Innes%2C%20Anna%20Dover%2C%20Karen%20Fairhurst%20-%20Macleod%E2%80%99s%20Clinical%20Examination-Elsevier%20%282018%29.pdf'),
  Book(
      id: 128,
      subject: 'Internal Medicine',
      title: 'DAVIDSON’S ESSENTIAL OF MEDICINE',
      writer: 'J. Alastair Innes',
      edition: '2nd',
      image:
          'https://www.medgag.com/wp-content/uploads/2018/02/Screenshot_2018-02-22-02-56-39-010_in.amazon.mShop_.android.shopping.png',
      rating: 4.8,
      description:
          '''For over half a century Davidson\'s Principles and Practice of Medicine has informed and educated students, doctors and other health professionals all over the world, providing a comprehensive account of the practice of medicine. Davidson\'s Essentials of Medicine provides the core content of the main textbook in a condensed format which will be invaluable whenever you are on the move - whether commuting, travelling between training sites, or on electives.''',
      link:
          'https://drive.google.com/uc?export=download&id=1ymnv_Cx8qMF-VscQfsGwWvGHUo3JMDLf'),
  Book(
      id: 129,
      subject: 'Internal Medicine',
      title: 'Davidson’s Principles and practice of medicine',
      writer:
          'Stuart H Ralston, Ian D Penman, Mark WJ Strachan, Richard P Hobson',
      edition: '23rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51VPjhDMcXL._SX366_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''More than two million medical students, doctors and other health professionals around the globe have owned a copy of Davidson’s Principles and Practice of Medicine since it was first published. Now in its 23rd Edition, this textbook describes the pathophysiology and clinical features of the most frequently encountered conditions in the major specialties of adult medicine and explains how to recognise, investigate, diagnose and manage them. Taking its origins from Sir Stanley Davidson’s much-admired lecture notes, Davidson’s has endured because it keeps pace with how modern medicine is taught and provides a wealth of information in an easy-to-read, concise and beautifully illustrated format. This book will serve readers everywhere as a core text that integrates medical science with clinical medicine, conveying key knowledge and practical advice in a highly accessible and readable format.

The opening section describes the fundamentals of genetics, immunology, infectious diseases and population health, and discusses the core principles of clinical decision-making and good prescribing.
A new second section on emergency and critical care medicine encompasses poisoning, envenomation and environmental medicine, and introduces a new chapter on acute medicine and critical illness.
The third section covers the major medical specialties, each thoroughly revised and brought fully up to date. Two new chapters on maternal and adolescent/transition medicine complement the one on ageing and disease. A new chapter on medical ophthalmology has been included.
Clinical Examination overviews summarise the main elements for each system and now feature in the biochemistry, nutrition and dermatology chapters.
Presenting Problems sections provide a clear pathway for the assessment of and approach to the most common complaints in each specialty.
Practice Point summaries detail the practical skills that medical students and junior doctors must acquire.
Emergency boxes emphasise the core knowledge needed to manage acutely ill patients.
In Old Age, In Pregnancy and In Adolescence boxes highlight differences in the practice of medicine in these patient groups, and illustrate the interfaces between medical, obstetric and paediatric services.
The text is extensively illustrated, with over 1000 diagrams, clinical photographs, and radiology and pathology images.
The global perspective is enhanced by an International Advisory Board of experts from 17 countries, and by authors from around the world.
The new second section on emergency and critical care medicine introduces a significantly expanded and comprehensive account of the approaches to dealing with acute medical and critical illness.
Two new chapters on maternal and adolescent/transition medicine complement the one on ageing and disease by addressing problems encountered at key stages of patients’ lives.
A new chapter on medical ophthalmology has been included as a direct response to readers’ requests.
The opening chapter has been completely rewritten with a new focus on the important principles of clinical decision-making or clinical reasoning.
A new internal text design for this 23rd Edition provides a simpler and clearer presentation of the various categories of text boxes.''',
      link:
          'http://93.174.95.29/main/2190000/a2be09d3cc6e39f3b18a77a17ceb4267/Stuart%20%20H%20%20Ralston%2C%20Ian%20%20D%20%20Penman%2C%20Mark%20%20WJ%20%20Strachan%2C%20Richard%20%20P%20%20Hobson%20-%20Davidson%E2%80%99s%20Principles%20and%20practice%20of%20medicine-Elsevier%20%282018%29.pdf'),
  Book(
      id: 130,
      subject: 'Internal Medicine',
      title: 'HUTCHISON’S CLINICAL METHODS',
      writer: 'J. Alastair Innes',
      edition: '24th',
      image:
          'https://www.medgag.com/wp-content/uploads/2018/03/20180315_003314.jpg',
      rating: 4.7,
      description:
          '''A textbook on clinical skills. It provides a source of learning and reference for undergraduate medical students and postgraduate doctors. It seeks to teach an integrated approach to clinical practice, so that new methods and investigations are grafted onto established patterns of clinical practice, rather than added on as something extra.''',
      link:
          'https://drive.google.com/uc?export=download&id=11RDAPnU4IEBo2Dqln8zwuk7XSx6Ip4eK'),
  Book(
      id: 131,
      subject: 'Internal Medicine',
      title: 'HARRISON’S INFECTIOUS DISEASES',
      writer: 'Anthony S. Fauci and Dennis Kasper',
      edition: '3rd',
      image:
          'https://www.medgag.com/wp-content/uploads/2018/11/Screenshot_2018_1104_100908.png',
      rating: 4.7,
      description:
          '''Harrison\'s Principles of Internal Medicine is an American textbook of internal medicine.[1] First published in 1950, it is in its 20th edition (published in August 2018 by McGraw-Hill Professional ISBN 978-1259644030) and comes in two volumes. Although it is aimed at all members of the medical profession, it is mainly used by internists and junior doctors in this field, as well as medical students. It is widely regarded as one of the most authoritative books on internal medicine and has been described as the "most recognized book in all of medicine.
The work is named after Tinsley R. Harrison of Birmingham, Alabama, who served as editor-in-chief of the first five editions and established the format of the work: a strong basis of clinical medicine interwoven with an understanding of pathophysiology.''',
      link:
          'https://drive.google.com/uc?export=download&id=1KanDZuaEOCDHoAXS3IasvCmtZZt02uz4'),
  Book(
      id: 132,
      subject: 'Internal Medicine',
      title: 'Davidson\'s 100 Clinical Cases',
      writer:
          'Mark W J Strachan BSc(Hons) MD FRCPE , Surendra K. Sharma MD PhD',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51TlHsqWHxL._SX331_BO1,204,203,200_.jpg',
      rating: 3.5,
      description:
          '''Davidson’s 100 Clinical Cases was awarded First Prize in Medicine in the 2009 British Medical Association Medical Book Awards. This book reflects the real world in which doctors practise medicine. The selection of clinical problems guides the reader, step by step, through the correct path in the maze between the presenting complaint of a patient and the final diagnosis. The text emphasises the value of interpreting available clinical and investigative information in a logical way before considering a definitive diagnosis.

The 100 cases are based on the ‘presenting problems’ of Davidson’s Principles and Practice of Medicine.
The book provides an international outlook reflecting the differences in the practice of medicine in the developing world and in low-resource settings, and addresses the epidemiological, economic and other reasons for many of these important differences.
The cases are written by a team of senior doctors, from 12 countries, with considerable teaching experience.
The book now includes 100 cases all closely linked to the ‘presenting problems’ sections of the latest 21st Edition of Davidson’s Principles and Practice of Medicine. In this expanded new edition there are many new cases including aluminium phosphide poisoning; occupational lung disease; tremor; and drug interactions.''',
      link:
          'https://drive.google.com/uc?export=download&id=1iFlbUU3X34UnqstfhoTjrzSlGghroQm6'),
  Book(
      id: 133,
      subject: 'Internal Medicine',
      title:
          'Clinical Medicine: A Textbook of Clinical Methods and Laboratory Investigations',
      writer: 'K. V. Krishna Das (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51vbuFgDvvL._SX346_BO1,204,203,200_.jpg',
      rating: 3.0,
      description:
          '''This new edition is a comprehensive guide to clinical medicine correlating clinical findings with pathological processes. Divided into two parts, the first section examines internal medicine and each of the systems in the human body. The second section discusses functions and processes of these systems.

Each chapter describes the investigation and examination of common disorders in each of the body systems. Nearly 700 full colour images and illustrations are included to enhance learning.''',
      link:
          'https://drive.google.com/uc?export=download&id=1_NAxk8CtdzQ7cI7E6X4Fpn4bA955t90S'),
  Book(
      id: 134,
      subject: 'Internal Medicine',
      title: 'The Principles and Practice of Medicine',
      writer: 'William Osler (Author)',
      edition: '2013',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41R7NQvRduL._SX382_BO1,204,203,200_.jpg',
      rating: 3.4,
      description:
          '''This historic book may have numerous typos and missing text. Purchasers can usually download a free scanned copy of the original book (without typos) from the publisher. Not indexed. Not illustrated. 1903 edition. Excerpt: ... SECTION XL DISEASES OF THE MUSCLES. I. MYOSITIS. Definition.--Inflammation of the voluntary muscles. A primary myositis occurs as an acute or subacute affection, and is probably dependent on some unknown infectious agent. Several characteristic cases have been described of late years. That of E. Wagner may be taken as a typical example. A tuberculous but well-built woman entered the hospital, complaining of stiffness in the shoulders and a slight oedema of the back of the hands and forearms. There was paresthesia, the arms became swollen, the skin tense, and the muscles felt doughy. Gradually the thighs became affected. The disease lasted about three months. The post mortem showed slight pulmonary tuberculosis; all the muscles except the glutei, the calf, and abdominal muscles were stiff and firm, but fragile, and there were serous infiltration, great proliferation of the interstitial tissue, and fatty degeneration. Similar cases have been reported by Unverricht, Hepp, and Jacoby, of New York. In the case reported by Jacoby the muscles were firm, hard, and tender, and there was slight oedema of the skin--dermato-myositis. The cases usually last from one to three months, though there are instances in which it has been longer. The swelling and tenderness of the muscles, the oedema, and the pain naturally suggest trichinosis, and indeed Hcpp speaks of it as a pseudo-trichinosis. The nature of the disease is unknown. Senator\'s case presented marked disorders of sensation, and there is a question whether the peripheral nerves are not involved with the muscles. Wagner suggests that some of these cases were examples of acute progressive muscular atrophy. The separation from trichinosis can be made only by removing a portion of the muscle. It...''',
      link:
          'https://drive.google.com/uc?export=download&id=1Q-NnPsi6UnBo47ViOYu-FbWpgm5F0iRD'),
  Book(
      id: 135,
      subject: 'Internal Medicine',
      title: 'CURRENT Medical Diagnosis and Treatment 2017',
      writer:
          'Maxine A. Papadakis(Author),Stephen J. McPhee (Author), Michael W. Rabow(Author)',
      edition: '56th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51VVllqfbZL._SX357_BO1,204,203,200_.jpg',
      rating: 4.5,
      description: '''eBook features:
Highlight, take notes, and search in the book
Length: 1920 pages 
Enhanced Typesetting: Enabled 
Page Flip: Enabled 
Similar books to CURRENT Medical Diagnosis and Treatment 2017 (Lange)
Due to its large file size, this book may take longer to download''',
      link:
          'https://drive.google.com/uc?export=download&id=1VHd78POu1rZKZoE18_Y-q8VH2uJljrTS'),
  Book(
      id: 136,
      subject: 'Internal Medicine',
      title: 'Kumar and Clark\'s Clinical Medicine',
      writer:
          'Parveen Kumar DBE BSc MD DM DEd FRCP FRCP(L&E) FRCPath FIAP (Editor), Michael L Clark MD FRCP (Editor)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51nAJ-4SzOL._SX395_BO1,204,203,200_.jpg',
      rating: 3.4,
      description:
          '''Kumar & Clark’s Clinical Medicine 8 builds on the prize-winning formula that won the first prize in the BMA Book Awards Medicine Category in 2010 (7th edition) and 2006 (6th edition).

‘This book is comprehensive, student friendly (if still intimidating in size!) and covers such a vast breadth of knowledge. It still remains the primary ‘must-have’ text book of any budding doctor, or qualified one at that. This book is stunning in its breadth and in its ease of use. It still remains as the ‘gold-standard’ thorough guide to clinical medicine its forefathers were.’ BMA Judges 2010

\'This is one of a select few books that deserves to be in most doctors\' personal possession and it\'s as simple as that. ...’ Dr Harry Brown.''',
      link:
          'https://drive.google.com/uc?export=download&id=1cBAauEn-j8ktCnDzXZZoZjx7mqtQy-aJ'),
  Book(
      id: 137,
      subject: 'Internal Medicine',
      title: 'Beside Clinicals In Medicine Part 1',
      writer: 'Kundu A K (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/31mPChwBJUL._BO1,204,203,200_.jpg',
      rating: 4.5,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1XlNiVgUQW4BF2n2-XSiLarAoFGECuP3J'),
  Book(
      id: 138,
      subject: 'Internal Medicine',
      title: 'Beside Clinicals In Medicine Part 2',
      writer: 'Kundu A K (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/518iyKjgY9L._SY498_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1YiHpA4oImUdAg_AKZeB5jUGOQ-Qje8Em'),
  Book(
      id: 139,
      subject: 'Internal Medicine',
      title:
          'Harrison’s Principles of Internal Medicine - 20th Edition: - Volume I & Volume II',
      writer:
          'J. Larry Jameson  (Author), Anthony S. Fauci (Author), Dennis L. Kasper (Author), Stephen L. Hauser (Author), Dan L. Longo (Author), Joseph Loscalzo (Author)',
      edition: '20th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/517Rrf%2BXquL._SY355_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1q-3N6AukVCPWXlKxjUKGMtw9TNmpDbf5'),
  Book(
      id: 140,
      subject: 'Internal Medicine',
      title: 'HARRISON’S ENDOCRINOLOGY',
      writer: 'Larry Jameson, J.  (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/515QN00ZOxL._SX386_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''Endocrinology – with all the authority of Harrison’s

A Doody\'s Core Title for 2019!

Featuring a superb compilation of chapters related to endocrinology derived from Harrison’s Principles of Internal Medicine, Nineteenth Edition (including content from the acclaimed Harrison’s DVD, now available here in print), this concise, full-color clinical companion delivers the latest knowledge in the field backed by the scientific rigor and authority that have defined Harrison’s.  You will find 36 chapters from 50 renowned editors and contributors in a carry-anywhere presentation that is ideal for the classroom, clinic, ward, or exam/certification preparation.

Features:

• Divided into six sections that reflect the physiologic roots of endocrinology: Introduction to Endocrinology; Pituitary, Thyroid, and Adrenal Disorders; Reproductive Endocrinology; Diabetes Mellitus, Obesity, Lipoprotein Metabolism; Disorders Affecting Multiple Endocrine Systems; and Disorders of Bone and Calcium Metabolism
• Coverage of discoveries emanating from genetics and molecular biology, along with the latest drugs that are transforming the field
• Integration of pathophysiology with clinical management
• High-yield board review questions make this text ideal for keeping current or preparing for the boards
• Valuable appendix of laboratory values of clinical importance''',
      link:
          'https://drive.google.com/uc?export=download&id=1VAGlklGJTQxM71YIvqbGr5wJydlhuQdh'),
  Book(
      id: 141,
      subject: 'Internal Medicine',
      title: 'Harrison\'s Nephrology and Acid-Base Disorders',
      writer: 'JAMESON (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51o9WC5v8qL._SX376_BO1,204,203,200_.jpg',
      rating: 3.1,
      description: '''Paperback: 336 pages
Publisher: MGH; 2nd edition (2013)
Language: English
ISBN-10: 0071814965
ISBN-13: 978-0071814966
ASIN: B0713Y3PPB''',
      link:
          'https://drive.google.com/uc?export=download&id=1JJ5cKdTjxMgyzL2C-BYCUEsft4P3a_wi'),
  Book(
      id: 142,
      subject: 'Internal Medicine',
      title: 'Harrison\'s Hematology and Oncology',
      writer: 'Dan L. Longo (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51AauSlpaiL._SX389_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''Hematology and Oncology – backed by the unmatched authority of Harrison’s

A Doody\'s Core Title for 2019!

Featuring a superb compilation of chapters related to hematology and oncology derived from Harrison’s Principles of Internal Medicine, Nineteenth Edition (including content from the acclaimed Harrison’s DVD, now available here in print), this concise, full-color clinical companion delivers the latest knowledge in the field backed by the scientific rigor and authority that have defined Harrison’s.  You will find 57 chapters from more than 75 renowned editors and contributors in a carry-anywhere presentation that is ideal for the classroom, clinic, ward, or exam/certification preparation.

Features:

• Each chapter contains relevant information on the genetics, cell biology, pathophysiology, and treatment of specific disease entities
• Chapters on hematopoiesis, cancer cell biology, and cancer prevention reflect the rapidly growing knowledge in these areas
• Integration of pathophysiology with clinical management
• High-yield board review questions make this text ideal for keeping current or preparing for the boards
• Valuable appendix of laboratory values of clinical importance''',
      link:
          'https://drive.google.com/uc?export=download&id=1O8Jj0Btg_WJTwal8ljrwJLy9dBuT-ZWL'),
  Book(
      id: 143,
      subject: 'Internal Medicine',
      title:
          'Harrison\'s Principles of Internal Medicine Self-Assessment and Board Review',
      writer:
          'Charles Wiener  (Author), Dennis L. Kasper (Author), Anthony S. Fauci (Author), Stephen L. Hauser (Author), Dan L. Longo (Author), Larry Jameson, J. (Author), Joseph Loscalzo (Author), Cynthia Brown (Author), Brain Houston (Author)',
      edition: '19th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/518y2%2Bc7-pL._SX389_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''Nothing prepares you for exam success like Harrison’s!

VIBRANT FULL-COLOR PRESENTATION INCLUDES COLOR ATLAS -- 500 ALL-NEW QUESTIONS!

Now you can add the unmatched authority of Harrison’s to your board review or test preparation. Based on the content of Harrison’s Principles of Internal Medicine, Nineteenth Edition, this rigorous study aid is essential for Internal Medicine Board certification or recertification/maintenance of certification, or as a refresher for any internal medicine examination.

Reflecting the accuracy, currency, and wide scope of Harrison’s, this complete review of internal medicine delivers more than 1,000  extremely challenging review questions, many of which utilize realistic patient scenarios, including radiographic and pathologic images. Each question is accompanied by explanations for correct and incorrect answers. These explanations -- which are derived from and cross-referenced to Harrison’s Principles of Internal Medicine, Nineteenth Edition – are one of the most effective ways to learn and teach internal medicine. They are designed to bolster your understanding of pathophysiology, epidemiology, differential diagnosis, clinical decision making, and therapeutics.

The format of the book has also been enhanced, allowing for a more effective use of color images throughout. Readers will appreciate the convenience of having color images next to their citations in the text.

A GREAT WAY TO LEARN INTERNAL MEDICINE:
• Coverage spans the entire spectrum of internal medicine
• Each topic is covered in proportion to its level of importance on the Internal Medicine Examination Blueprint
• Approximately 500 NEW, never-before-published Q&As (more than 60% of the questions are NEW!)
• Includes full-color atlas
• Content follows the organization of Harrison’s Principles of Internal Medicine, Nineteenth Edition – making it perfect for side-by-side study
• Beautiful full-color presentation''',
      link:
          'https://drive.google.com/uc?export=download&id=1XfZRSR0k-rbTMiRnJmqKKV4mCCT_YrkW'),
  Book(
      id: 144,
      subject: 'Internal Medicine',
      title: 'Harrison\'s Rheumatology',
      writer: 'Anthony S. Fauci (Author), Carol A. Langford (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51r-D01nFdL._SX387_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''Rheumatology – as only Harrison’s can cover it

A  Doody\'s Core Title for 2019!

Featuring a superb compilation of chapters related to rheumatology derived from Harrison’s Principles of Internal Medicine, Nineteenth Edition (including content from the acclaimed Harrison’s DVD, now available here in print), this concise, full-color clinical companion delivers the latest knowledge in the field backed by the scientific rigor and authority that have defined Harrison’s.  You will find 24 chapters from more than 35 renowned editors and contributors in a carry-anywhere presentation that is ideal for the classroom, clinic, ward, or exam/certification preparation. 

FEATURES

• Current, thorough coverage of important immunology and rheumatology topics, including the immune system in health and disease, disorders of immune-mediated injury, and disorders of the joints and adjacent tissues
• Delivers insights designed to reduce pain, lesson joint and organ damage, and improve overall patient outcomes
• Integrates pathophysiology with clinical management
• High-yield board review questions make this text ideal for keeping current and preparing for the boards
• Helpful appendix of laboratory values of clinical importance''',
      link:
          'https://drive.google.com/uc?export=download&id=11ADtaYq32sSK87YnrXzQ83y6mYCDHjuh'),
  Book(
      id: 145,
      subject: 'Internal Medicine',
      title: '100 Cases in Acute Medicine',
      writer:
          'Kerry Layne  (Author), Henry Fok (Author), Adam Nabeebaccus (Author)',
      edition: '1st',
      image: 'https://images-eu.ssl-images-amazon.com/images/I/41ZuDBJqfdL.jpg',
      rating: 4.9,
      description:
          '''100 Cases in Acute Medicine presents 100 acute conditions commonly seen by medical students and junior doctors in the emergency department, or on the ward, or in the community setting. A succinct summary of the patient\'s history, examination, and initial investigations, including photographs where relevant, is followed by questions on the diagnosis and management of each case. The answer includes a detailed discussion of each topic, with further illustration where appropriate, providing an essential revision aid as well as a practical guide for students and junior doctors.

Making clinical decisions and choosing the best course of action is one of the most challenging and difficult parts of training to become a doctor. These cases will teach students and junior doctors to recognize important clinical symptoms and signs, and to develop their diagnostic and management skills.''',
      link:
          'https://drive.google.com/uc?export=download&id=1kCI5Shki8RQzdibOxQIUsbt7oGxam9xw'),
  Book(
      id: 146,
      subject: 'Internal Medicine',
      title: 'Harrison\'s Gastroenterology and Hepatology',
      writer:
          'Dennis L. Kasper (Author), Anthony S. Fauci (Author), Stephen Hauser (Author), Dan L. Longo (Author), J. Larry Jameson (Author), & 1 more',
      edition: '3rd',
      image: 'https://images-eu.ssl-images-amazon.com/images/I/511BtGY-kDL.jpg',
      rating: 4.9,
      description:
          '''Featuring a superb compilation of chapters related to gastroenterology and hepatology derived from Harrison’s Principles of Internal Medicine, Nineteenth Edition (including content from the acclaimed Harrison’s DVD, now available here in print), this concise, full-color clinical companion delivers the latest knowledge in the field backed by the scientific rigor and authority that have defined Harrison’s. You will find 63 chapters from more than 80 renowned editors and contributors in a carry-anywhere presentation that is ideal for the classroom, clinic, ward, or exam/certification preparation.

FEATURES

• Coverage includes: cardinal manifestations of disease, evaluation of the patient, disorders of the alimentary tract, infections of the alimentary tract, disorders of the liver and biliary tree, liver transplantation, disorders of the pancreas, neoplastic diseases of the gastrointestinal system, nutrition, and obesity and eating disorders

• Reflects the most current advances in genetics, cell biology, pathophysiology, and treatment

• Integration of pathophysiology with clinical management

• High-yield board review questions make this text ideal for keeping current and preparing for the boards

• Helpful appendix of laboratory values of clinical importance''',
      link:
          'https://drive.google.com/uc?export=download&id=1GV4aeXBVgOECocvZGut3oWq-l6lL_Bs0'),
  Book(
      id: 147,
      subject: 'Internal Medicine',
      title: '100 Cases in Clinical Medicine',
      writer:
          'P John Rees (Author), James Pattison (Author), Christopher Kosky  (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41N3KO9Jr3L._SX343_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''Making speedy and appropriate clinical decisions and then choosing the best course of action is an essential skill for doctors. Exploring initial medical assessment, 100 Cases in Clinical Medicine presents 100 scenarios commonly seen by medical students and junior doctors in the emergency or outpatient department, on the ward, or in the community setting.

Each case begins with a succinct summary of the patient\'s history, examination, and initial investigation. The text includes photographs where relevant and questions on the diagnosis and management of each case. The answers provide a detailed discussion on each topic, with further illustration where appropriate.

Most of the cases included are common problems but the book also includes more unusual cases to illustrate specific points and to emphasize that rare things do present. The first 20 cases are arranged by systems; the next 80 are in random order because symptoms such as breathlessness and pain may relate to many different clinical problems in various systems.

These true-to-life cases will teach students and junior doctors to recognize important clinical symptoms and signs and to develop the diagnostic and management skills needed for the cases they will encounter on the job.''',
      link:
          'https://drive.google.com/uc?export=download&id=1MwkWsYA7E1-6m_jBGBYl7z27LYqJ02cu'),
  Book(
      id: 148,
      subject: 'Internal Medicine',
      title: 'Harrison\'s Neurology in Clinical Medicine',
      writer: 'Stephen Hauser (Author), S. Andrew Josephson (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51gnZdQE8XL._SX389_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''Featuring a superb compilation of chapters related to neurology derived from Harrison’s Principles of Internal Medicine, Nineteenth Edition (including content from the acclaimed Harrison’s DVD, now available here in print), this concise, full-color clinical companion delivers the latest knowledge in the field backed by the scientific rigor and authority that have defined Harrison’s.  You will find 66 chapters from more than 90 renowned editors and contributors in a carry-anywhere presentation that is ideal for the classroom, clinic, ward, or exam/certification preparation.

Features:

• High-yield board review questions make this text ideal for keeping current and preparing for the boards
• Current, complete coverage of clinically important topics in neurology, including Clinical Manifestations of Neurologic Diseases, Diseases of the Nervous System, Chronic Fatigue Syndrome, Psychiatric Disorders, and Alcoholism and Drug Dependency
• Extensively updated to highlight recent advances in the understanding, diagnosis, treatment, and prevention of neurologic and psychiatric disorders; expanded coverage of neurodegenerative diseases; extensively revised chapter on cerebrovascular diseases; the latest breakthroughs in sleep disorders and migraine
• Integration of pathophysiology with clinical management
• Enhanced by numerous neuroimaging figures throughout the text and an expanded atlas of neuroimaging findings
• Handy appendix of Laboratory Values of Clinical Importance''',
      link:
          'https://drive.google.com/uc?export=download&id=1jnq_KoACIzTTc1Q-X83kXTgAQ5QbYzeM'),
  Book(
      id: 149,
      subject: 'Internal Medicine',
      title: 'Harrison\'s Pulmonary and Critical Care Medicine',
      writer: 'Joseph Loscalzo (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51CsBa7N-PL._SX389_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''Featuring a superb compilation of chapters related to pulmonary and critical care topics derived from Harrison’s Principles of Internal Medicine, Nineteenth Edition (including content from the acclaimed Harrison’s DVD, now available here in print), this concise, full-color clinical companion delivers the latest knowledge in the field backed by the scientific rigor and authority that have defined Harrison’s.  You will find 45 chapters from more than 70 renowned editors and contributors in a carry-anywhere presentation that is ideal for the classroom, clinic, ward, or exam/certification preparation.

Features:

• Logically divided into five sections that reflect the scope of pulmonary and critical care medicine: Diagnosis of Respiratory Disorders, Diseases of the Respiratory System, General Approach to the Critically Ill Patient, Common Illnesses and Syndromes, and Disorders Complicating Critical Illnesses and Their Management
• Integration of pathophysiology with clinical management
• High-yield board review questions make this text ideal for keeping current or preparing for the boards
• Valuable appendix of laboratory values of clinical importance''',
      link:
          'https://drive.google.com/uc?export=download&id=1GP8ojathVgVZaESbNST-EYMvbz1APJYx'),
  Book(
      id: 150,
      subject: 'Internal Medicine',
      title: 'Harrison\'s Cardiovascular Medicine',
      writer: 'Joseph Loscalzo (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41khQfnbwbL._SX388_BO1,204,203,200_.jpg',
      rating: 3.9,
      description: '''Paperback
Publisher: McGraw-Hill Medical (1703)
ASIN: B0161T9NT2''',
      link:
          'https://drive.google.com/uc?export=download&id=19KgaTCFvE2qKibgaa2-gd_xnVXkSqZ-S'),
  Book(
      id: 151,
      subject: 'Internal Medicine',
      title:
          'Golwalla’s Medicine for Students (A Reference Book for the Family Physician)',
      writer:
          'Aspi F Golwalla (Author), Sharukh A Golwalla (Author), Milind Y Nadkar (Author)',
      edition: '25th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41byJNfxg1L._SX362_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''Golwalla’s Medicine for Students, at times labelled as Bible in medicine has been a byword not only for students of allopathy but also those of dentistry, homeopathy, physiotherapy and even Ayurveda. The book by no means claims to be a standard textbook but has gained its increasing popularity over the years from the point of view of helping the undergraduate students to answer commonly asked question in both theory and viva-voce. Adequate number of tables, electrocardiographs and up-to-date investigations, including radiological, have been included to enhance its readable value. A number of family physicians are known to use this book as a reference volume because of its updated information on both diagnosis and treatment of maladies, both common and some uncommon.''',
      link:
          'https://drive.google.com/uc?export=download&id=1E-ZQkN1Cx12RcdhrkkBcazbM3qQaEqfZ'),
  Book(
      id: 152,
      subject: 'Internal Medicine',
      title: 'Medicine: PreTest Self Assessment and Review',
      writer: 'William R. Davis, Robert S. Urban Steven L. Berk (Author)',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41SIN32CbBL._SX322_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1Pq85rWcas5CdHI5Fbv3MjO7j7uwhP4PY'),
  Book(
      id: 153,
      subject: 'Internal Medicine',
      title:
          'Review of Post Graduate Medical Entrance Examination (PGMEE)|Vol 1',
      writer: 'Arvind Arora, Amit Tripathi Amit Gupta (Author, Contributor)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51KLn91SeyL._SX383_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''This book is very useful for students on medical entrance examinations, it covers topics from all subjects. 3 volumes are compiled and OCR done. Easy to search & practice.''',
      link:
          'http://93.174.95.29/main/2064000/63008752879a083e051743cfc522be05/Amit%20Tripathi%2C%20Arvind%20Arora%2C%20Ashish%20Gupta%20-%20Review%20of%20Post%20Graduate%20Medical%20Entrance%20Examination%20%28PGMEE%29%20%5BAAA%5D.%201-3-Pulse%20Publ.%20%282013%29.pdf'),
  Book(
      id: 154,
      subject: 'Internal Medicine',
      title: 'Medicine MCQs for Medical Professionals (PGMEE)',
      writer: 'Mathur Ajay',
      edition: '3rd',
      image:
          'https://am-medicine.com/wp-content/uploads/2016/01/Medicine-MCQs-for-Medical-Professionals.jpg',
      rating: 3.8,
      description:
          '''Specifically written for those preparing for examinations and practitioners in travel medicine, MCQs in Travel Medicine contains over 600 multiple choice questions with detailed explanations which both teach and challenge the reader.

Questions are group by topic which is ideal for revision, enabling you to focus on specific areas including adventure travel, travellers’ diarrhoea, malaria, sexually transmitted disease, and drugs used in travel medicine. The style and format of the questions mirror the format of the exam questions, and the book includes a self-test to aid revision.

This easy-to-read comprehensive book is ideally suited for those in busy day-to-day practices and those preparing for examinations in travel medicine including the Certificate Exam of the International Society of Travel Medicine.''',
      link:
          'http://93.174.95.29/main/2324000/e7af53f7cc720137c47aaa196b590cb0/Mathur%20Ajay%20-%20Medicine%20MCQs%20for%20Medical%20Professionals%20%28PGMEE%29-Jaypee%20%282014%29.pdf'),
  Book(
      id: 155,
      subject: 'Internal Medicine',
      title: 'CURRENT Medical Diagnosis and Treatment 2020',
      writer:
          'Maxine A. Papadakis (Author), Stephen J. McPhee  (Author), Michael W. Rabow (Author)',
      edition: '59th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/5121wZnM8KL._SX361_BO1,204,203,200_.jpg',
      rating: 4.0,
      description:
          '''The #1 annual internal medicine guide that clinicians turn to first―extensively revised and updated
 
CURRENT Medical Diagnosis & Treatment is the most comprehensive, reliable, and timely reference available to answer common questions that arise in everyday clinical practice. Written by clinicians renowned in their respective fields, this trusted classic offers expert advice on all aspects of outpatient and inpatient medical care. You’ll find authoritative, evidence-based coverage of more than 1,000 diseases and disorders including concise, yet thorough synopsis of diagnosis and treatment. Presented in full-color, this single source reference has been fully updated with the latest developments and breakthroughs in medicine, guidelines, references, drug prices, and more.
 
This essential clinical companion features:
 
• A strong emphasis on the practical aspects of clinical diagnosis and patient management
• Detailed review of all internal medicine disciplines, including geriatrics, preventive medicine, and palliative care, plus gynecology and obstetrics, dermatology, ophthalmology, neurology, psychiatry, and more
• An annual update on HIV/AIDS and other new, emerging viral infections
• Specific information regarding disease prevention and prognosis
• Medication treatment tables, with indexed trade names and updated prices
• Key recent references on each topic with PMID numbers for quick online access
• Many full-color photographs, tables, figures and other illustrations

Here are some of the many updates and additions:
 
• Extensive updating of tables and images
• New FDA-approved medication for multiple sclerosis
• New summary of recommended FDA treatment regimens for hepatitis C
• U.S. Preventive Services Task Force recommendations for osteoporosis, prostate cancer, ovarian cancer, and cervical cancer
• Extensive update of immune modulation therapy and adjuvant treatments of breast cancer
• Targeted therapies for advanced non-small cell lung cancers
• Thoroughly revised chapter on viral and rickettsial infections, including recent measles, polio, and acute flaccid paralysis outbreaks, and on related immunizations
• Clarification of the appropriate role of opioids and buprenorphine formulations in chronic pain management
• Revised section on health care for sexual and gender minority patients
• Information on new biologic agents for asthma, and many other disorders''',
      link:
          'https://drive.google.com/uc?export=download&id=1tsvkO9j_1dhjji2SA7dZS81cLtGJt3br'),
  Book(
      id: 156,
      subject: 'Internal Medicine',
      title: 'Medicine: Prep Manual for Undergraduates',
      writer: 'K. George Mathew, Praveen Aggarwal',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41i-YpBVvpL._SX383_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''The fifth edition of this book is in a must-have for all undergraduate medical students as it prepares them for both theory and viva-voce examinations. It is also useful for dentistry and nursing students. Structured in question-answer format, this book presents a concise exam-oriented text as per the guidelines of Medical Council of India and health universities across the country.

Main Features of the Book

Presents the text in question-answer format which helps the student in quick learning and revision
Topics presented in points with suitable boxes, tables, flowcharts and diagrams to facilitate easy understanding and revision
Highlights of the Fifth Edition

Extensively revised, updated, and strengthened to keep up with the latest changes in the field of medicine
Large number of tables, flowcharts to facilitate quick learning and greater retention of knowledge
Thoroughly revised chapters on respiratory system, cardiovascular system, oncology, diseases of kidneys
Systemize presentation to make reading soothing and pleasurable by deleting redundant details, adding new text without changing basic framework
Inclusion of clinical decision pathways for some of the commonly encountered critical and non-emergent disease conditions
Inclusion of newer innovations and treatments modalities''',
      link:
          'http://93.174.95.29/main/2273000/c46e517941a2f45cb8c10d998c639a8f/K.%20George%20Mathew%2C%20Praveen%20Aggarwal%20-%20Medicine_%20Prep%20Manual%20for%20Undergraduates-Elsevier%20India%20%282015%29.pdf'),
  Book(
      id: 157,
      subject: 'Internal Medicine',
      title: 'CASE FILES INTERNAL MEDICINE',
      writer:
          'Eugene C. Toy (Author), John T. Patlan (Author), Mark T Warner (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51ZReOUIMSL._SX332_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''SHARPEN YOUR CRITICAL THINKING SKILLS AND IMPROVE PATIENT CARE

Experience with clinical cases is key to mastering the art and science of medicine and ultimately in providing patients with competent clinical care. Case Files®: Internal Medicine provides 60 true-to-life cases that illustrate essential concepts in Internal Medicine. Each case includes an easy-to-understand discussion correlated to key concepts, definitions of key terms, clinical pearls, and board-style review questions to reinforce your learning. With Case Files®, you’ll learn instead of memorize.

• Learn from 60 high-yield cases, each with board-style questions, and conveniently organized by related diagnosis
• Master key concepts with clinical pearls
• Cement your knowledge with 25 new integrated challenge questions
• Polish your approach to clinical problem solving and to patient care
• Perfect for medical students and physician assistant students''',
      link:
          'http://93.174.95.29/main/1640000/84c4441a6d5d6be168dd05bd55067396/%28LANGE%20Case%20Files%29%20Eugene%20Toy%2C%20John%20Patlan%2C%20Mark%20T.%20Warner%20-%20Internal%20Medicine-McGraw-Hill%20%282017%29.pdf'),
  Book(
      id: 158,
      subject: 'Internal Medicine',
      title: 'Cecil Textbook of Medicine: Single Volume (Cecil Medicine)',
      writer: 'Lee Goldman, Dennis Ausiello',
      edition: '22th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51q4Xp7PVhL._SX390_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''Hardcover
Publisher: Saunders; 22 edition (1707)
ASIN: B011DAT2AE''',
      link:
          'http://93.174.95.29/main/173000/06723649d984f7836fc2bf8f001aaff0/%28Cecil%20Medicine%29%20Lee%20Goldman%2C%20Dennis%20Ausiello%20-%20Cecil%20Textbook%20of%20Medicine-Saunders%20%282003%29.pdb'),
  Book(
      id: 159,
      subject: 'Surgery',
      title: 'MANIPAL MANUAL OF SURGERY',
      writer: 'Anthony S. Fauci and Dennis Kasper',
      edition: '4th',
      image:
          'https://www.medgag.com/wp-content/uploads/2018/05/20180509_232800.jpg',
      rating: 4.7,
      description:
          '''This is the completely revised, thoroughly rewritten & carefully updated new edition of the most popular Manual, specially aimed at undergraduate & medical students. The limited time-frame available to the under-graduate students makes it necessary for them to be able to read a good comprehensive book reliably and this edition fully meets just that requirement.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Yt4gS7i_q9IbdiSMktNZBtzEssnxoiY9'),
  Book(
      id: 160,
      subject: 'Surgery',
      title: 'BAILEY & LOVE’S SHORT PRACTICE OF SURGERY',
      writer: 'Henry Hamilton Bailey',
      edition: '27th',
      image:
          'https://www.medgag.com/wp-content/uploads/2017/11/AA8FCCFF-DAFA-4F6A-AB86-833178C3B8EC.jpeg',
      rating: 4.1,
      description:
          '''Bailey & Love\'s Short Practice of Surgery is one of the world\'s pre-eminent medical textbooks with worldwide sales of over one million copies.''',
      link:
          'https://drive.google.com/uc?export=download&id=1qRWkPa6xoX3idwZm_z4z1ThwheMCFrda'),
  Book(
      id: 161,
      subject: 'Surgery',
      title: 'S. Das Manual on Clinical Surgery',
      writer: 'Dr Somen Das',
      edition: '13th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/A1xamg7DOKL._SL1500_.jpg',
      rating: 4.0,
      description:
          '''Performing surgery on the human body is no small task and A Manual On Clinical Surgery is one of the most useful books when it comes to this field of medicine. Considered to be unmatched among books in its category, it comes in handy for those who are about to enter the surgical wards and conduct surgery. A Manual On Clinical Surgery gives you a detailed explanation of everything that you will need to know about performing clinical surgery. Packed with supporting information, that includes color and monochrome prints, radiography and line drawings - it is the foremost guide for students who are going to write their MBBS examination. The text is supplemented with almost 648 illustrations giving you a clear understanding of each body part.''',
      link:
          'https://drive.google.com/uc?export=download&id=1wkiVOWaY_m6PmQRXEZuzLuM4kQOTLUpQ'),
  Book(
      id: 162,
      subject: 'Surgery',
      title: 'SRB’s Manual of Surgery,',
      writer: 'Dr Somen Das',
      edition: '5Th Edition',
      image:
          'https://www.medgag.com/wp-content/uploads/2018/10/IMG_20181018_131517.jpg',
      rating: 4.1,
      description:
          '''• Exclusive photographs and illustrations relevant to the topics covered 
• Recent grading and staging of malignant conditions along with recent trend in therapeutic modalities are been discussed wherever necessary 
• Additional more boxes and notes are added in appropriate places.''',
      link:
          'https://drive.google.com/uc?export=download&id=1yuwg0YKhkHuY86NSxJFqO4cKuYPRJIRz'),
  Book(
      id: 163,
      subject: 'Surgery',
      title: 'Bedside Clinics in Surgery',
      writer: 'Makhan Lal Saha (Author)',
      edition: '2nd Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/519R31vwVPL._SX362_BO1,204,203,200_.jpg',
      rating: 4.6,
      description: '''• Practically almost all the sections have been revised.
• Special emphasis is given for elicitation of different physical signs.
• All surgical problems -emergency and non-emergency are discussed including important X-ray plates.
• Operating section includes all the steps of important operations.
• The TNM classification of all the malignant tumors has been updated.
• Surgical anatomy section discussed exclusive hand drawn illustrations and tried to correlate the anatomy portion with short and long cases.
• All the short and long cases are discussed with lots of color photographs and schematic diagrams.
What is NEW in the Third Edition?
• The concept of exact measurement of a swelling has been incorporated by using a Vernier caliper instead of a tape measurement.
• A new long case on management of diabetic foot has been added in the long case section.
• In X-ray section interpretation of mammography has been added.
• In surgical anatomy section, lower leg compartments and cervical fascia have been added.
• About 30-40 new figures added as per the requirement of the main text.''',
      link:
          'https://drive.google.com/uc?export=download&id=125HeyV2jUp308twuuiklyHLOVnrWu3EN'),
  Book(
      id: 164,
      subject: 'Surgery',
      title: 'Schwartzs Principles of Surgery',
      writer: '',
      edition: '10Th Edition',
      image:
          'https://accessmedicine.mhmedical.com/data/books/980/cover_9780071796750_fc.jpeg',
      rating: 4.1,
      description:
          '''For half-a-century, no other text has provided such a solid grounding in basic science, anatomy, operative techniques, and more recently, professional development and leadership training, as Schwartz’s Principles of Surgery. Written by the world’s foremost surgeons, this landmark reference offers distinctly modern and all-encompassing coverage of every important topic in general surgery. 

Enhanced by a new two volume presentation, the Eleventh Edition has been completely updated and refreshed with an emphasis on state-of-the-art, evidence-based surgical care.  You will find an exciting array of new contributors from around the world, new chapters on cutting-edge topics, plus the acclaimed learning aids that make the material easier to understand and memorize. This outstanding content is bolstered by more than 800 photographs and 1,300 line drawings, most in full color, as well as online videos demonstrating key operations.

Here’s why the Eleventh Edition is the best edition yet:

Six timely new chapters on important topics such as enhanced recovery after surgery (ERAS), ambulatory/outpatient surgery, evidence for surgery practice, skills and simulation, and web-based education and social media

High-quality full-color design showcases an unsurpassed illustration program

Emphasis on high-yield discussion of diagnosis and treatment of surgical disease, arranged by organ system and surgical specialty

Acclaimed learning aids (many new to this edition), including an abundance of completely up-to-date tables that summarize the most current evidence, boxed key points, detailed anatomical figures, diagnostic and management algorithms, and an abundance of completely up-to-date tables, and key references

More than the field’s cornerstone textbook, Schwartz’s Principles of Surgery is an international compendium of the knowledge and technique of the world’s leading surgeons.''',
      link:
          'https://drive.google.com/uc?export=download&id=10ozTZ3dSQRF9uW2ceuM67g7erIrFV_AW'),
  Book(
      id: 165,
      subject: 'Surgery',
      title:
          'Sabiston Textbook of Surgery: The Biological Basis of Modern Surgical Practice',
      writer: 'Courtney M. Townsend Jr. (Author), R. Daniel Beauchamp (Author)',
      edition: '20Th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51ORbtZwbXL._SX399_BO1,204,203,200_.jpg',
      rating: 4.1,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1vOCTyYLdgxRWUIWUtvrINtFKaVPcwEHH'),
  Book(
      id: 166,
      subject: 'Surgery',
      title: 'Farquharson\'s Textbook of Operative General Surgery',
      writer:
          'Margaret Farquharson  (Editor), James Hollingshead (Editor), Brendan Moran (Editor)',
      edition: '10Th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51E9FhE%2BUpL._SX382_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''First published in 1954, Farquharson\'s Textbook of Operative General Surgery has become firmly established as a classic textbook for trainee surgeons throughout the world. Basic surgical techniques, including the reasons for their application, are discussed. General surgical operations are described and the indications for them are covered. Techniques are described in sufficient detail to allow a surgeon who has limited experience of a particular operation to proceed with confidence and safety. The text is thus also valuable for surgeons practising in smaller hospitals worldwide where specialised advice may not otherwise be available.''',
      link:
          'https://drive.google.com/uc?export=download&id=1S9QXQDCcrZx8p7hXIaEoGbnPQDRIh6Dg'),
  Book(
      id: 167,
      subject: 'Surgery',
      title:
          'Hamilton Bailey\'s Physical Signs: Demonstrations of Physical Signs in Clinical Surgery',
      writer:
          'John S.P Lumley (Author), Anil K. D\'Cruz  (Author), Jamal J. Hoballah  (Author), Carol E.H. Scott-Connor (Author)',
      edition: '19Th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/411sAV9%2BJkL._SX378_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''First published in 1954, Farquharson\'s Textbook of Operative General Surgery has become firmly established as a classic textbook for trainee surgeons throughout the world. Basic surgical techniques, including the reasons for their application, are discussed. General surgical operations are described and the indications for them are covered. Techniques are described in sufficient detail to allow a surgeon who has limited experience of a particular operation to proceed with confidence and safety. The text is thus also valuable for surgeons practising in smaller hospitals worldwide where specialised advice may not otherwise be available.''',
      link:
          'https://drive.google.com/uc?export=download&id=1c5LtB88NtoXDCm1XHH_cVErH7IZz9tFZ'),
  Book(
      id: 168,
      subject: 'Surgery',
      title: 'Churchill\'s Pocketbook of Surgery (Churchill Pocketbooks)',
      writer: '',
      edition: '5Th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/413xFTN0LVL._SX294_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''The Fifth Edition of this highly-praised and bestselling pocketbook continues to deliver a concise and didactic account of the essential features of all common surgical disorders. The book covers fundamental principles as well as providing basic information on aetiology, diagnosis and management, including pre-operative and post-operative care. The text includes an overview of history-taking, relevant physical signs, differential diagnosis, investigations and practical treatment.''',
      link:
          'https://drive.google.com/uc?export=download&id=1c5LtB88NtoXDCm1XHH_cVErH7IZz9tFZ'),
  Book(
      id: 169,
      subject: 'Surgery',
      title: 'SRB\'s Clinical Methods in Surgery',
      writer: '',
      edition: '2010',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41uAKFf4DpL._SX378_BO1,204,203,200_.jpg',
      rating: 5.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1IgZ5N9g300X3pNQTqyIP6JzXJ5oWDCfX'),
  Book(
      id: 170,
      subject: 'Surgery',
      title: 'MCQs and EMQs in Surgery: A Bailey & Love Companion Guide',
      writer:
          'Christopher Bulstrode (Author), B.V. Praveen (Author), Pradip Datta (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/419d8XNaBCL._SX336_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1N-8Wr48tlaKlao3xCqR9mGAa5UpNeNju'),
  Book(
      id: 171,
      subject: 'Surgery',
      title: 'Otolaryngology - Head and Neck Surgery',
      writer: 'Anil Lalwani',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51DZ81bqsSL._SX394_BO1,204,203,200_.jpg',
      rating: 3.5,
      description:
          '''A concise, one-stop clinician’s guide for treating all major diseases of the ear, nose, throat, and neck

CURRENT Diagnosis & Treatment Otolaryngology spans the entire breadth of ENT topics, including the latest developments in basic science, facial plastic surgery, head and neck surgery, laryngology, rhinology, pediatric otolaryngology, otology, and neurotology. This find-it-now clinician\'s guide includes commonly encountered as well as unusual diseases of the head and neck and is essential for board review and recertification.

Features and Highlights

Conveniently organized by anatomic region
Consistent presentation includes General Considerations, Pathogenesis, Prevention, Clinical Findings, Differential Diagnosis, and Treatment
Must-know medical and surgical management of each disorder
Thorough discussion of pathophysiology and relevant basic and clinical science
More than 400 state-of-the-art clinical photographs and line drawings
Comprehensive radiology chapter with more than 150 images
“Essentials of Diagnosis” section for each disease and disorder delivers key points at a glance''',
      link:
          'http://93.174.95.29/main/1711000/78a3b481fde94602490d3d55f3ff7292/%28Lange%20Current%20Diagnosis%20%26%20Treatment.%29%20Anil%20Lalwani%20-%20Otolaryngology%20-%20Head%20and%20Neck%20Surgery-McGraw-Hill%20%282011%29.pdf'),
  Book(
      id: 172,
      subject: 'Pediatric',
      title: 'Ghai Essential Pediatrics',
      writer: 'Vinod K. Paul',
      edition: '8th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51k4yMFGi5L._SX438_BO1,204,203,200_.jpg',
      rating: 4.0,
      description:
          '''Ghai Essential Paediatrics 2013, 8th Edition covers diagnosis and treatment associated with child health care. This book is written and published by renowned and proficient child health care experts and serves as a reliable knowledge resource for students of Paediatrics, both graduate and undergraduate. For over 25 years the book has been setting a benchmark in terms of imparting knowledge in Paediatrics Health and Education sector.''',
      link:
          'https://drive.google.com/uc?export=download&id=1zMUUkK9-Wv6JUlbszfMKT8C92Gg34tDN'),
  Book(
      id: 173,
      subject: 'Pediatric',
      title: 'THE SHORT TEXTBOOK OF PEDIATRICS',
      writer: 'SURAJ GUPTE',
      edition: '11th Edition',
      image:
          'https://www.medgag.com/wp-content/uploads/2018/01/IMG_20180122_170139-808x1024.jpg',
      rating: 4.6,
      description:
          '''The Short Textbook of Pediatrics - Suraj Gupte 11th Edition. Recommended book for Pediatrics. Most of the students refer Gupte. It is a good book for Pediatrics.''',
      link:
          'https://drive.google.com/uc?export=download&id=1uPOel7Zw3wB-SsdUhCzue4aNVVw6ahMz'),
  Book(
      id: 174,
      subject: 'Pediatric',
      title: 'BRS Pediatrics',
      writer: 'Lee Todd Miller and Lloyd J. Brown',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/510mvZzOcSL._SX348_BO1,204,203,200_.jpg',
      rating: 4.2,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1gWVVh_CnT2VRCDdcVyWW8iysiPvIlbBl'),
  Book(
      id: 175,
      subject: 'Pediatric',
      title: 'Nelson Textbook of Pediatrics',
      writer:
          'Robert M. Kliegman MD , Bonita M.D. Stanton MD , Joseph St. Geme MD, Nina F Schor MD PhD (Author), Richard E. Behrman MD',
      edition: '20th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41-kP%2BiZ-KL._SX390_BO1,204,203,200_.jpg',
      rating: 3.7,
      description:
          '''Nelson Textbook of Pediatrics has been the world’s most trusted pediatrics resource for nearly 75 years. Drs. Robert Kliegman, Bonita Stanton, Richard Behrman, and two new editors - Drs. Joseph St. Geme and Nina Schor - continue to provide the most authoritative coverage of the best approaches to care. This streamlined new edition covers the latest on genetics, neurology, infectious disease, melamine poisoning, sexual identity and adolescent homosexuality, psychosis associated with epilepsy, and more. Best of all, the expanded online access at Expert Consult features the full text, case studies, new references and journal articles, Clinics articles, and exclusive web-only content so that you get even more out of this invaluable reference.''',
      link:
          'https://drive.google.com/uc?export=download&id=1AToZNsy3U3-mdzhimUjioVZDP_1iIi4g'),
  Book(
      id: 176,
      subject: 'Pediatric',
      title: 'Clinical Paediatrics History Taking And Case Discussion',
      writer: 'Aruchamy Lakshmanaswamy (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51sLOg6VSxL._SY331_BO1,204,203,200_.jpg',
      rating: 5.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1zpEYI4UOWdFRgnY0jUpSQktWnA5xDJ7A'),
  Book(
      id: 177,
      subject: 'Pediatric',
      title: 'Caffey\'s Pediatric Diagnostic Imaging, 2-Volume Set',
      writer: 'Brian D. Coley MD (Author)',
      edition: '12th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/518WtLcHS8L._SX383_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Since 1945, radiologists have turned to Caffey\'s Pediatric Diagnostic Imaging for the most comprehensive coverage and unparalleled guidance in all areas of pediatric radiology. Continuing this tradition of excellence, the completely revised 12th edition - now more concise yet still complete - focuses on the core issues you need to understand new protocols and sequences, and know what techniques are most appropriate for given clinical situations. "This text will obviously be of great interest not only to radiologists, also to those who work with children including all pediatric specialties. It is also extremely useful in countries with resource poor setting where there is shortage of well-trained radiologists in pediatric specialties." Reviewed by: Yangon Children Hospital on behalf of the Journal of the European Paediatric Neurology Society, January 2014''',
      link:
          'https://drive.google.com/uc?export=download&id=1zpEYI4UOWdFRgnY0jUpSQktWnA5xDJ7A'),
  Book(
      id: 178,
      subject: 'Pediatric',
      title: 'Clinical Pediatrics',
      writer: 'Aruchamy Lakshmanaswamy (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41%2BC4oIVZqL._SX368_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''This book is part of the LWW India publishing program. This program is developed for the Indian market working with Indian authors who are the foremost experts in their respective fields. Our Indian authors do research and teach at the most respected Indian medical schools and academic hospitals.Specially designed for medical students, this book presents a succinct exposition of the clinical procedures involved in the diagnosis and management of common pediatric cases''',
      link:
          'https://drive.google.com/uc?export=download&id=1xV7jZZk0NpMRBGIUUrDAZ7GQ0AEwUqk6'),
  Book(
      id: 179,
      subject: 'Pediatric',
      title: 'Handbook of Pediatric Neuro-Ophthalmology (Springer Handbook of)',
      writer: 'Kenneth W. Wright (Editor)',
      edition: '2006th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41PMuQVgxrL._SX310_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''Based on Dr. Wright’s classic major reference, Handbook of Pediatric Neuroophthalmology outlines the latest findings in diagnosing children\'s eye diseases and their treatment options. Distilling the essentials of ocular manifestations of pediatric neuroophthalmologic disorders and diseases into a portable, complete and authoritative pocket reference, this handbook offers a complete picture of how to best treat pediatric patients. Specifically, the introductory chapters on the specifics of pediatric ophthalmology (embryology, post-natal development and the pediatric exam) will help newcomers to pediatric practice fully grasp the subtle differences in pediatric care. The chapters are written by leading experts in the field and are presented in a user-friendly format, relying on heavily illustrated in color plates, clinically helpful tables, charts, and decision-making guidelines. This approach will enable the practitioner (whether specialist or generalist) to make the most accurate diagnosis and choose the most effective treatment option.''',
      link:
          'https://drive.google.com/uc?export=download&id=1UYbTQc0YZZg4P2d2hYeMjm9FYh5Gyv8J'),
  Book(
      id: 180,
      subject: 'Pediatric',
      title: 'Nelson Textbook of Pediatrics, 2-Volume Set',
      writer:
          'Robert M. Kliegman MD (Author), Bonita Stanton MD (Author), Joseph St. Geme MD (Author), Nina F Schor MD PhD (Author),',
      edition: '20th',
      image:
          'https://i.pinimg.com/originals/ef/70/1d/ef701dcc0491e4d7051cdb4254c91781.jpg',
      rating: 4.0,
      description:
          '''Nelson Textbook of Pediatrics has been the world\'s most trusted pediatrics resource for nearly 75 years. Drs. Robert Kliegman, Bonita Stanton, Richard Behrman, and two new editors - Drs. Joseph St. Geme and Nina Schor - continue to provide the most authoritative coverage of the best approaches to care. This streamlined new edition covers the latest ongenetics, neurology, infectious disease, melamine poisoning, sexual identity and adolescent homosexuality, psychosis associated with epilepsy, and more. Best of all, the expanded online access atExpert Consult features the full text, case studies, new references and journal articles, Clinics articles, and exclusive web-only content so that you get even more out of this invaluable reference.''',
      link:
          'https://drive.google.com/uc?export=download&id=1UYbTQc0YZZg4P2d2hYeMjm9FYh5Gyv8J'),
  Book(
      id: 181,
      subject: 'Pediatric',
      title: 'Nelson Textbook of Pediatrics',
      writer:
          'Robert M. Kliegman MD (Author), Bonita M.D. Stanton MD (Author), Joseph St. Geme MD (Author), Nina F Schor MD PhD (Author)',
      edition: '20th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51LLZtEA0NL._SX389_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''After more than 75 years, Nelson Textbook of Pediatrics remains your indispensable source for definitive, state-of-the-art answers on every aspect of pediatric care. Embracing the new advances in science as well as the time-honored art of pediatric practice, this classic reference provides the essential information that practitioners and other care providers involved in pediatric health care throughout the world need to understand to effectively address the enormous range of biologic, psychologic, and social problems that our children and youth may face. Brand-new chapters and comprehensive revisions throughout ensure that you have the most recent information on diagnosis and treatment of pediatric diseases based on the latest recommendations and methodologies.

 

"The coverage of such a wide range of subjects relating to child health makes this textbook still the gold standard and companion for all pediatricians across the world." Reviewed by Neel Kamal, Sept 2015

 

"All in all, this is an excellent and detailed paediatric review textbook which represents excellent value for money..truly a textbook for the global community" Reviewed by glycosmedia.com, Sept 2015

Form a definitive diagnosis and create the best treatment plans possible using evidence-based medicine and astute clinical experiences from leading international authors―many new to this edition.
A NEW two-volume layout provides superior portability and exceptional ease of use.

Gain a more complete perspective. Along with a broader emphasis on imaging and molecular diagnoses and updated references, the new edition includes an increased focus on international issues to ensure relevance in pediatrics practice throughout the world.
Effectively apply the latest techniques and approaches with complete updates throughout 35 new chapters, including: Innovations in Addressing Child Health and Survival in Low Income Settings; Developmental Domains and Theories of Cognition; The Reggio Emilia Educational Approach Catatonia ; Refeeding Syndrome; Altitude-associated Illness; Genetic Approaches to Rare and Undiagnosed Diseases; Healthcare-Associated Infections; Intrapartum and Peripartum Infections; Bath salts and other drugs of abuse; Small Fiber Polyneuropathy; Microbiome; Kingella kingae; Mitochondrial Neurogastrointestinal Encephalomyopathy; Nonalcoholic Fatty Liver Disease; Plagiocephaly; CNS Vasculitis; Anterior Cruciate Ligament Rupture; and Sports-Related Traumatic Brain Injury.
Recognize, diagnose, and manage genetic and acquired conditions more effectively. A new Rehabilitation section with 10 new chapters, including: Evaluation of the Child for Rehabilitative Services; Severe Traumatic Brain Injury; Spinal Cord Injury and Autonomic Crisis Management; Spasticity; Birth Brachial Plexus Palsy; Traumatic and Sports-Related Injuries; Meningomyelocele; Health and Wellness for Children with Disabilities.
Manage the transition to adult healthcare for children with chronic diseases through discussions of the overall health needs of patients with congenital heart defects, diabetes, and cystic fibrosis.
Understand the principles of therapy and which drugs and dosages to prescribe for every disease.
Expert Consult eBook version included with purchase. This enhanced eBook experience allows you to search all of the text, figures, and references from the book on a variety of devices.''',
      link:
          'https://drive.google.com/uc?export=download&id=1YzK1dtVv6BihQxtonEP6zU37TdCKOIvw'),
  Book(
      id: 182,
      subject: 'Pediatric',
      title: 'MCQs in Pediatrics Review of Nelson Textbook of Pediatrics',
      writer:
          'Robert M. Kliegman MD, Bonita M.D. Stanton MD, Joseph St. Geme MD, Nina F Schor MD PhD',
      edition: '20th',
      image:
          'https://freemedworld.com/wp-content/uploads/2018/07/IMG_20180709_201156_018-275x300.jpg',
      rating: 4.0,
      description:
          '''After more than 75 years, Nelson Textbook of Pediatrics remains your indispensable source for definitive, state-of-the-art answers on every aspect of pediatric care. Embracing the new advances in science as well as the time-honored art of pediatric practice, this classic reference provides the essential information that practitioners and other care providers involved in pediatric healthcare throughout the world need to understand to effectively address the enormous range of biologic, psychologic, and social problems that our children and youth may face. Brand-new chapters and comprehensive revisions throughout ensure that you have the most recent information on diagnosis and treatment of pediatric diseases based on the latest recommendations and methodologies.''',
      link:
          'https://drive.google.com/uc?export=download&id=1evuc13ENhs-TbC6Fm1tESosY3AzeGPSD'),
  Book(
      id: 183,
      subject: 'Gyno/obs',
      title: 'DC DUTTA’S TEXTBOOK OF GYNECOLOGY',
      writer: 'Konar Hiralal (Author)',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51TbCfWZfpL._SX369_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''This new edition has been fully revised to present the latest developments in gynaecology. Beginning with an introduction to the anatomy and development of female pelvic organs, the following chapters describe the diagnosis and treatment of both common and rare gynaecological diseases and disorders.''',
      link:
          'https://drive.google.com/uc?export=download&id=1ABK_qDKUa6AJTtvIAU_B5_Msmdt_RLk4'),
  Book(
      id: 184,
      subject: 'Gyno/obs',
      title: 'DC Dutta’s Textbook of OBSTETRICS',
      writer: 'Konar Hiralal (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51oM9exU05L._SX367_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''This new edition has been fully revised to present the latest developments in gynaecology. Beginning with an introduction to the anatomy and development of female pelvic organs, the following chapters describe the diagnosis and treatment of both common and rare gynaecological diseases and disorders.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Ju1rzfccNF3zm2QRH-bFunfis7UUINyy'),
  Book(
      id: 185,
      subject: 'Gyno/obs',
      title: 'Williams Obstetrics',
      writer: 'Kenneth J. Leveno',
      edition: '24th',
      image:
          'https://www.medgag.com/wp-content/uploads/2018/04/20180412_122904.jpg',
      rating: 4.9,
      description:
          '''Williams Obstetrics is the most detailed, comprehensive, and rigorously referenced text on the subject. Written by an author team from the world-renowned Parkland Hospital, the hallmarks of this classic are its thoroughness, scientific basis, and practical applicability for the obstetrician at the bedside. This edition of Williams Obstetrics continues to emphasize the scientific-based underpinnings and evidence-based practices of the specialty. This is accomplished by using incorporating more than 3,000 new literature citations and guidelines from the most trusted professional and academic organizations.''',
      link:
          'https://drive.google.com/uc?export=download&id=15KPlDKAO9ZiE5FJpras2OBY4KPNhpr3v'),
  Book(
      id: 186,
      subject: 'Gyno/obs',
      title: 'Shaw’s  Textbook of Gynaecology',
      writer:
          'V. G. Padubidri (Editor), Shirish N Daftary MD DGO FICS FICOG (Editor)',
      edition: '16th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51u0TGGAAuL._SX385_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''Shaw\'s Textbook of Gynaecology, one of the best-selling gynaecological textbooks of all time, has maintained its popularity with teachers, examiners and students. It is now in its 79th year of publication. The organization of content in this book is such that it provides the reader with a logical sequence of events that aid learning.''',
      link:
          'https://drive.google.com/uc?export=download&id=1MgB2iP8boxr9iVrAKeSzK7Kn5gtAy2i2'),
  Book(
      id: 187,
      subject: 'Gyno/obs',
      title: 'Obstetrics by Ten Teachers',
      writer: 'Louise C. Kenny (Editor), Jenny E. Myers (Editor)',
      edition: '19th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41PCusdZ5eL._SX372_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''First published in 1917 as \'Midwifery\', Obstetrics by Ten Teachers is well established as a concise, yet comprehensive, guide within its field. The twentieth edition has been thoroughly updated by a new team of \'teachers\', integrating clinical material with the latest scientific developments that underpin patient care. Each chapter is highly structured, with learning objectives, definitions, aetiology, clinical features, investigations, treatments, case histories and key point summaries and additional reading where appropriate. New themes for this edition include \'professionalism\' and \'global health\' and information specific to both areas is threaded throughout the text. Along with its companion Gynaecology by Ten Teachers the book will continue to provide an accessible \'one stop shop\' in obstetrics and gynaecology for a new generation of doctors.''',
      link:
          'https://drive.google.com/uc?export=download&id=15qubenPM9v2RItiy6xu-tzbJL65CfuWS'),
  Book(
      id: 188,
      subject: 'Gyno/obs',
      title: 'Gynaecology Illustrated',
      writer:
          'Catrina Bain MBChB MRCOG (Author), Kevin Burton MD MRCOG (Author), Jay McGavigan MBBS MD MRCOG FRANZCOG (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51iKbs69liL._SX382_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''This is a visual presentation of Gynaecology aimed at undergraduate medical students. The highly effective format is ideal for examination preparation. Each page covers one topic with concise text and associated diagrams. Previously under the authorship of Hart and Norman, the new author has comprehensively revised the sixth edition of this very popular student text. The titles in the illustrated series are valued by students because of their visual presentation of information and are particularly effective for examination preparations. For the more traditional courses this book will fulfil the role of a course text; for problem-based courses it will be an excellent resource for problem-solving exercises.''',
      link:
          'https://drive.google.com/uc?export=download&id=1j1cGGIARayOIukbf_5S8yQ_mVberjUjv'),
  Book(
      id: 189,
      subject: 'Gyno/obs',
      title: 'Case Discussions In Obstetrics & Gynecology',
      writer:
          'Catrina Bain MBChB MRCOG (Author), Kevin Burton MD MRCOG (Author),Jay McGavigan MBBS MD MRCOG FRANZCOG (Author)',
      edition: '2011',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/31G1zE%2BaGuL._BO1,204,203,200_.jpg',
      rating: 5.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=12ojAJTwwreSmwwVRPQUCioM9gx_MNfYP'),
  Book(
      id: 190,
      subject: 'Gyno/obs',
      title:
          'Dutta\'S Bedside Clinics And Viva-Voce In Obstetrics & Gynecology',
      writer:
          'Catrina Bain MBChB MRCOG (Author), Kevin Burton MD MRCOG (Author),Jay McGavigan MBBS MD MRCOG FRANZCOG (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51OCzC7-kjL._SX362_BO1,204,203,200_.jpg',
      rating: 4.0,
      description:
          '''Covers comprehensively the entire zone of Clinical, Practical and Viva-Voce part of the examination, fulfilling University course curriculum.
Answers are framed in a simple and concise way for easy understanding and reproduction.
Immensely helpful for quick revision of the entire course, to those having a background of Textbook knowledge.
Model answers are made to guide a candidate how to write the theory questions (short questions chapters both in obstetrics and gynecology section).
Topics on Ultrasonography, Doppler studies, Computed Tomography (CT), Magnetic Resonance Imaging (MRI), Positron Emission Tomography (PET), Laparoscopic and Hysteroscopic Surgery, Robotic Surgery have been incorporated extensively to acquaint a candidate with the progress of Science and technology.
SBAs and MCQs are presented with model answers for wide coverage of the subject and to make up the weak areas.
Exhaustive number of clinical photographs, graphs, sketches and line drawings has been included for better understanding of difficult areas.
Authoritative and comprehensive synoptic guide for the Clinical and Viva-Voce part of the examination.
Above all, the information is up-to-date, evidence-based, and the reading is simple and enjoyable.''',
      link:
          'https://drive.google.com/uc?export=download&id=1pI8BbY4CKSbHgYQS6qQZaaY7GpHOzc4h'),
  Book(
      id: 191,
      subject: 'Gyno/obs',
      title: 'Deja Review Obstetrics & Gynecology',
      writer: 'Emily S Miller  (Author), Catherine J. Lee  (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51SSIH8O2ZL._SX329_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''"Flashcards in a book" provide a comprehensive yet concise review for the obstetrics and gynecology clerkship

Deja Review: Obstetrics & Gynecology boils down your coursework to just the critical concepts you need to know for exam success. This unbeatable guide features a quick-read, two-column, “flashcard in a book” Q&A format. – specifically designed to help you remember a large amount of pertinent information in the least amount of time possible. The format allows you to zero-in on only the correct answers to promote memory retention and get the most out of your study time. Great for last minute review of high-yield facts, Deja Review provides a straightforward way for you to assess your strengths and weaknesses so you can excel on the clerkship and the USMLE Step 2 CK.

Comprehensive multiple-choice Q&A chapter at the end of the book.
Active recall questions allow you to understand, not just memorize the content
Clinical vignettes at the end of chapters prepare you for board-style questions
Portable size for study on the go – fits into your coat pocket
Bookmark included to guide you through easy-to-use flashcard presentation''',
      link:
          'https://drive.google.com/uc?export=download&id=1gl-NVTf17cz_HIg0kfCuGekxOPGYzRmk'),
  Book(
      id: 192,
      subject: 'Gyno/obs',
      title: '100 Cases in Obstetrics and Gynaecology',
      writer: 'Cecilia Bottomley  (Author), Janice Rymer (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41MStPDs0EL._SX345_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1a4Yo0SCKmzs0VgtHOagLGJPmTeGA7nF0'),
  Book(
      id: 193,
      subject: 'Gyno/obs',
      title: 'MCQs for Obstetrics and Gynaecology',
      writer: '',
      edition: '',
      image: '',
      rating: 1.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=130KMlbLYacFrlVZnXuyNp0ZpTaZMCtbp'),
  Book(
      id: 194,
      subject: 'Gyno/obs',
      title: 'Case Files High-Risk Obstetrics (LANGE Case Files)',
      writer:
          'Eugene C. Toy (Author), Edward R Yeomans (Author), Linda Fonseca (Author), Joseph M. Ernest (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41rTGPbL78L._SX329_BO1,204,203,200_.jpg',
      rating: 4.1,
      description: '''Real patients, real cases teach you high-risk obstetrics

"This is an excellent handbook on high risk obstetrics. The ideal audience is medical students or residents in the field who like real life scenarios to accentuate their learning. It is best suited for those in a time crunch, and residents and students certainly qualify. 3 Stars."--Doody\'s Review Service

Case Files: High-Risk Obstetrics uses fifty clinical cases to illustrate evidence-based practice in high-risk obstetrics patients. Each case includes open-ended questions, extended discussion, Practice Pearls, a “Controversy” discussion, comprehension questions, and references to the most current literature with a brief critique of each article. This unique learning system teaches you to be a better clinician by learning in the context of real patients and reinforcing the latest evidence-based medicine.

Features

Clear and easy-to-follow case-based format helps residents and fellows develop clinical thinking skills
Based on current journal articles and landmark studies, with an accompanying brief critique
"Practical Pearls" give evidence-based recommendations for patient management
"Controversy" feature discusses current controversies and different views related to each case
Multiple-choice comprehension questions accompany each case
Original line drawings and clinical images
Proven learning system improves exam scores''',
      link:
          'http://93.174.95.29/main/778000/e23f7f2845062b8b4792c346ed98a8c4/Eugene%20Toy%2C%20Edward%20Yeomans%2C%20Linda%20Fonseca%2C%20Joseph%20Ernest%20-%20Case%20Files%20High-Risk%20Obstetrics%20%281st%20Edition%29%20%20-McGraw-Hill%20Companies%2C%20The%20%282010%29.mobi'),
  Book(
      id: 195,
      subject: 'Gyno/obs',
      title: 'Case Files Gynecologic Surgery (LANGE Case Files)',
      writer:
          'Eugene C. Toy (Author), Konrad P. Harms (Author), Keith Reeves (Author), Cristo Papasakelariou (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41yNnoFj7jL._SX331_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Case Files: Gynecologic Surgery provides 40 clinical cases to illustrate evidence-based practice in the gynecologic surgery patient. Each case includes open-ended questions, extended discussion, Practice Pearls, a “Controversy” discussion, comprehension questions, and references to the most current literature with a brief critique of each article. With this unique learning system you\'ll learn how to become a better clinician in the context of real patients and the latest evidence-based medicine.

Features

40 high-yield clinical situations tailored for management and understanding of disease (pathophysiology) in the gynecologic surgery patient
Clear and easy-to-follow case-based format helps residents and fellows develop clinical thinking skills
Based on current journal articles and landmark studies, with an accompanying brief critique
"Practical Pearls" give evidence-based recommendations for patient management
"Controversy" feature discusses current controversies and different views related to each case
Multiple-choice comprehension questions accompany each case
Approximately 25 original drawings and clinical images enhance the text
Presents high-yield high-risk gynecologic surgery cases in an interactive and memorable format to help residents and fellows learn in the context of real patients
Proven learning system improves exam scores''',
      link:
          'http://93.174.95.29/main/726000/0f31acd2669bdb5b7f5ee15932b585b1/Eugene%20Toy%2C%20Konrad%20Harms%2C%20Keith%20Reeves%2C%20Cristo%20Papasakelariou%20-%20Case%20Files%20Gynecologic%20Surgery%20%281st%20Edition%29%20%20-McGraw-Hill%20Companies%2C%20The%20%282010%29.mobi'),
  Book(
      id: 196,
      subject: 'Gyno/obs',
      title: 'CASE FILES OBSTETRICS AND GYNECOLOGY',
      writer:
          'Eugene Toy (Author), Patti Ross (Author), Benton Baker (Author), John Jennings (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51mjwHax-7L._SX331_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''SHARPEN YOUR CRITICAL THINKING SKILLS AND IMPROVE PATIENT CARE
Experience with clinical cases is key to mastering the art and science of medicine and ultimately to providing patients with competent clinical care. Case Files®: Obstetrics & Gynecology provides 60 true-to-life cases that illustrate essential concepts in obstetrics and gynecology. Each case includes an easy-to-understand discussion correlated to key concepts, definitions of key terms, clinical pearls, and USMLE®-style review questions to reinforce your learning. With Case Files®, you’ll learn instead of memorize.

·       Learn from 60 high-yield cases, each with board-style questions

·       Master key concepts with clinical pearls''',
      link:
          'http://93.174.95.29/main/2069000/123c471e05fdd3262abda91e949c1843/Eugene%20C.%20Toy%2C%20Patti%20Jayne%20Ross%2C%20Benton%20Baker%20III%2C%20John%20Jennings%20-%20Case%20Files%20Obstetrics%20and%20Gynecology-McGraw-Hill%20%282016%29.pdf'),
  Book(
      id: 197,
      subject: 'Gyno/obs',
      title: 'RAPID OBSTETRICS AND GYNAECOLOGY',
      writer: 'Misha Moore (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41DmopTxBtL._SX322_BO1,204,203,200_.jpg',
      rating: 3.5,
      description:
          '''This pocket reference and revision guide is a must for all medical students and junior doctors preparing for major exams in obstetrics and gynaecology or needing a rapid reminder during a clinical attachment. Now thoroughly updated, this second edition has been re-ordered into three sections - covering obstetrics, gynaecology, and procedures - to provide a more systematic and ordered approach to learning that takes into consideration the natural division within the specialty. Covering all key topics in Obstetrics and Gynaecology, this succinct account of the core and common conditions found in clinical settings and exams is the ideal refresher covering just the basic, relevant facts.''',
      link:
          'http://93.174.95.29/main/1287000/dc00c0a0fbfc031a475ec19bab0fc8be/%28Rapid%20series%29%20Misha%20Moore_%20Sarah%20Jane%20Lam_%20Adam%20R%20Kay%20-%20Rapid%20obstetrics%20%26%20gynaecology-Wiley-Blackwell%20%282010%29.pdf'),
  Book(
      id: 198,
      subject: 'Gyno/obs',
      title: 'OBSTETRICS AND GYNECOLOGY AT A GLANCE',
      writer: 'Errol R. Norwitz  (Author), John O. Schorge  (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41pilsE2gHL._SX389_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''This comprehensively updated new edition provides a thorough and dynamically-illustrated overview of the female reproductive organs, care of the female during pregnancy, childbirth and the postnatal period. It is clinically relevant, with a focus on diagnosing, managing and treating disorders and abnormalities and is fully aligned with medical school curricula.

Obstetrics and Gynecology at a Glance:
• Recaps basic history taking, anatomy and endocrinology and focuses on clinically relevant information
• Covers each topic in a double-page spread, packed with charts, graphs, photographs and visuals
• Includes thoroughly updated sections on reproductive endocrinology, infertility and urogynecology

The companion website at www.ataglanceseries.com/obgyn features interactive flashcards, case studies and multiple-choice questions (MCQs).

Obstetrics and Gynecology at a Glance is the perfect guide for medical students, junior doctors and midwives, and is ideal for those embarking on clinical rotations and the clerkship.''',
      link:
          'http://93.174.95.29/main/1171000/a0c210a3384254f599e5ec53659e9fb0/Errol%20R.%20Norwitz%2C%20John%20O.%20Schorge%20-%20Obstetrics%20and%20Gynecology%20at%20a%20Glance-Wiley-Blackwell%20%282013%29.pdf'),
  Book(
      id: 199,
      subject: 'Gyno/obs',
      title: 'NETTER’S OBSTETRICS AND GYNECOLOGY',
      writer: 'Smith MD, Roger P. (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51xFSnkm9CL._SX370_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Now fully up to date with numerous new chapters and Expert Consult online access, Netter\'s Obstetrics and Gynecology, 3rd Edition , by Roger P. Smith, MD, provides superbly illustrated coverage of the common conditions and problems most often encountered in ob/gyn practice. Classic Netter images are paired with concise, evidence-based descriptions of common diseases, conditions, diagnostics, treatments, and protocols. Large, clear illustrations and short, to-the-point text make this the perfect reference for everyday clinical practice as well as staff and patient education.

More than 300 exquisite Netter images, as well as new, recent paintings by Carlos Machado provide a quick and memorable overview of each disease or condition.
Concise text and a standardized format provide quick access to expert medical thinking.
Entirely new sections on Embryology and Anatomy contain chapters on Sexual Differentiation, Genital Tract Development, Development of the Breast, and each area of gynecologic anatomy.
New chapters on Chronic Pelvic Pain, BRCA1 and BRCA2 mutations, Obstetric Anesthesia and Analgesia, Subdermal Contraceptive Capsule Insertion and Removal, Trigger Point Injections, and more.
NEW! Expert Consult™ eBook version included with purchase. This enhanced eBook experience allows you to search all of the text, figures, and references from the book on a variety of devices, and includes access to 26 patient education brochures.''',
      link:
          'http://93.174.95.29/main/2206000/4f3765b832028d400d504306e4b5f244/Roger%20Smith%20-%20Netter%E2%80%99s%20Obstetrics%20and%20Gynecology-Elsevier%20%282017%29.pdf'),
  Book(
      id: 200,
      subject: 'Gyno/obs',
      title: 'LECTURE NOTES OBSTETRICS AND GYNAECOLOGY',
      writer: 'Diana Hamilton–Fairley  (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/418SGZx0rAL._SX346_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Now in its 3rd edition, Lecture Notes: Obstetrics and Gynaecology has been extensively revised and updated to provide a concise and practical introduction to obstetrics and gynaecology for medical students and junior doctors. Starting with a section on basic science, the text is divided into six sections that explain female health needs and their management from the early years to old age. The self-assessment section is now a separate chapter, and includes Extended Matching Questions (EMQs), scenarios for practical history taking for the Objective Structured Clinical Examination (OSCE) and Multiple Choice Questions (MCQs). Part 1 looks at female reproductive anatomy and physiology. Part 2 covers the puberty and menstrual problems of young women, sub-fertility, pregnancy prevention, and sexual problems. Part 3 examines the reproductive years including pregnancy and childbirth. Part 4 covers the mature woman including menstrual problems of the older woman and pelvic pain. Part 5 discusses the older woman including the menopause, incontinence and malignancy including breast cancer. Part 6 demonstrates the importance of public health statistics on the provision of services in obstetrics and gynaecology. Now in two-colour throughout, with a new colour plate section, Lecture Notes: Obstetrics and Gynaecology covers the core material needed for O&G courses, written specifically for medical students, nursing students, junior doctors on the Foundation Programme and the first two years of specialist training, midwives, and GPs.''',
      link:
          'http://93.174.95.29/main/166000/dfd2c7dc86dd10f4c513940124e62bc8/%28Lecture%20Notes%29%20Diana%20Hamilton-Fairley%20-%20Lecture%20notes%20on%20obstetrics%20and%20gynaecology-Wiley-Blackwell%20%282004%29.pdf'),
  Book(
      id: 201,
      subject: 'Gyno/obs',
      title: '100 CASES IN OBSTETRICS AND GYNAECOLOGY',
      writer: 'Cecilia Bottomley  (Author), Janice Rymer (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41MStPDs0EL._SX345_BO1,204,203,200_.jpg',
      rating: 2.9,
      description:
          '''100 Cases in Obstetrics and Gynaecology presents 100 commonly seen obstetric and gynaecological scenarios. The patient\'s history, examination and initial investigations are presented along with questions on the diagnosis and management of each case. The answer includes a detailed discussion on each topic, providing an essential revision aid as well as a practical guide for junior clinicians.



Making clinical decisions is one of the most challenging and difficult parts of training to become a doctor. These cases will teach medics and medical students to recognize important obstetric and gynaecological conditions and help them develop their diagnostic and management skills.''',
      link:
          'https://ia601408.us.archive.org/7/items/222nd100casobfsgsfsgynbogfftrym2nd/222nd%20100%26cas%26obs%26gyn%26bot%26rym%262nd.pdf'),
  Book(
      id: 202,
      subject: 'Gyno/obs',
      title: 'SAKSHI ARORA HANS SELF ASSESSMENT & REVIEW GYNECOLOGY',
      writer: 'Hans Sakshi Arora (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51kS7Bd8lVL._SX390_BO1,204,203,200_.jpg',
      rating: 3.6,
      description:
          '''Free interactive DVD-ROM contains live lecture on \'Amenorrhea\' (duration 3 hrs.). Bestseller book on Gynecology thoroughly revised and updated edition including latest exam pattern and image based questions. Contains lucid presentation of text in a new layout. Includes recent questions of AIIMS 2015 and PGI 2013. Includes more than 200 new pattern questions. Color plates of \'Instruments, Specimens and Radiology\' in Gynecology are given in a separate section. Annexures for last minute revision included for the first time. Includes new stagings, new treatment modalities and new HPV vaccine. Important HSGs and hysteroscopic view included for the first time. Must read for undergraduates, foreign medical graduates, interns, all postgraduate medical aspirants and for any exam of Gynecology.''',
      link:
          'https://drive.google.com/uc?export=download&id=1XaZV94YH-QUl5GP07D0oWwI5HnVtuRw8'),
  Book(
      id: 203,
      subject: 'Forensic Science',
      title: 'Simpson’s Forensic Medicine',
      writer: 'Richard Jones (Author), Steven B Karch (Author)',
      edition: '12th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51WfnJ98f-L._SX381_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''Since the first edition was published in 1947, Simpson\'s Forensic Medicine has become the classic introduction to forensic medicine and pathology. Written by one of the leading forensic pathologists in the field, this new edition is completely up-to-date and revised to include information on living subjects.''',
      link:
          'https://drive.google.com/uc?export=download&id=1tFJBbx3bfCC1lB8nE6nC5xqSNxVLVZxR'),
  Book(
      id: 204,
      subject: 'Forensic Science',
      title: 'The essential of forensic medicine & toxicology',
      writer: 'Reddy Narayan (Author)',
      edition: '33th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51WkIkQi-ZL._SY498_BO1,204,203,200_.jpg',
      rating: 3.9,
      description: '''Entirely revised and updated with medicolegal cases. 
• Concise, easy-to-grasp and streamlined presentation. 
• Illustrated with diagrams, photographs, tables and important points. 
• Important topics are dealt in detail to meet the requirements of
medical officers such as Forensic Ballistics, Regional Injuries, Anesthetic and Operative Deaths, DNA Fingerprinting and
Blood Stains, etc. 
• A few new topics, such as procedure to be followed in dealing
with medicolegal cases, virtual autopsy have been incorporated. 
• Text printed in smaller type is meant for medical officers
undertake medicolegal work, medical practitioners, members of
the legal profession and other law enforcement officers. 
• Must-have for undergraduate medical students, postgraduate
students, medical teachers and officers and lawyer.''',
      link:
          'https://drive.google.com/uc?export=download&id=1X3HYnW0TPz6GPFECZScBbyc05jQHeGeq'),
  Book(
      id: 205,
      subject: 'Forensic Science',
      title: 'Color Atlas of the Autopsy',
      writer: 'Scott A. Wagner (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51%2BaFFxe7YL._SX366_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''Standing over the autopsy table gives you an unparalleled perspective on every element of the autopsy procedure. Remarkable details of disease and injury appear right before your eyes, presenting a complete picture that leads you in the direction of death. Now, those striking images have been taken from the table to the text in the only full-color guide to all aspects of the autopsy.

Forensic pathology is a visual discipline, making images essential to properly explaining the critical process. Featuring over 500 full-color photographs, Color Atlas of the Autopsy provides unadulterated access to every probe of the autopsy procedure. As the only atlas to focus on autopsy protocol, the book introduces the process and principles of the procedure to uninitiated professionals who interact with the pathologist before, during, and after the autopsy. This incomparable guide presents an astonishing visual experience that goes beyond a demonstration to demystify the autopsy.''',
      link:
          'https://drive.google.com/uc?export=download&id=1lQC6QFMRtg9rfhAGgyqU2L48bhsJubhU'),
  Book(
      id: 206,
      subject: 'Forensic Science',
      title: 'Review of Forensic Medicine and Toxicology',
      writer:
          'Gautam Biswas  (Author), Joseph A. Prahlow (Foreword), Anil Aggrawal (Foreword)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51CWh3VdZsL._SX363_BO1,204,203,200_.jpg',
      rating: 2.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1t8HoMlsRmIW2gaDcGrGZoNYDr4g8xDSb'),
  Book(
      id: 207,
      subject: 'Forensic Science',
      title: 'OXFORD HANDBOOK OF PRACTICAL ETHICS',
      writer: 'Hugh LaFollette  (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51rPqWbMmpL._SX346_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''The Oxford Handbook of Practical Ethics is a lively and authoritative guide to current thought about ethical issues in all areas of human activity--personal, medical, sexual, social, political, judicial, and international, from the natural world to the world of business. Twenty-eight topics are covered in specially written surveys by leading figures in their fields: each gives an authoritative map of the ethical terrain, explaining how the debate has developed in recent years, engaging critically with the most notable work in the area, and pointing directions for future work. The Handbook will be essential reading, and a fascinating resource of ideas and information, for academics and students across a wide range of disciplines.''',
      link:
          'http://93.174.95.29/main/401000/5119741c443e53f16ea178ffd09f98e0/%28Oxford%20Handbooks%29%20Hugh%20LaFollette%20-%20The%20Oxford%20Handbook%20of%20Practical%20Ethics%20-Oxford%20University%20Press%2C%20USA%20%282005%29.pdf'),
  Book(
      id: 208,
      subject: 'Forensic Science',
      title: 'Textbook of Forensic Medicine and Toxicology',
      writer: 'Nageshkumar G Rao (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41K6Nha2pdL._SX370_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''Expanded, revamped and revised completely, with recent advances and current developments. Five major parts with 40 concise chapters, as well as appendices and index covering over 600 pages. Around 700 excellent original coloured photographs and over 500 hundred plain drawings, charts, tables and boxes. More than 1500 references from reputed journals, textbooks and websites. Simple English language with consistency in style. Easy to understand, revise and reproduce to excel in the examinations. Attains working knowledge for future professional sphere. Student friendly text, with least strain to the eyes. Frequent plain/bold and normal/italic fonts with bullets to emphasize credibility. Systematic presentation of coloured heading and subheadings. Fully multi-coloured printing on quality paper, yet reasonably priced. Laws relating to Medical Profession. MCI recommended Syllabus and Examination Methodology. Separate UG and PG Theory and Viva-Voce Question Bank.''',
      link:
          'https://ia601507.us.archive.org/3/items/BookNageshFm/Nageshkumar%20Forensic%20medicine-www.medicosideas.com.pdf'),
  Book(
      id: 209,
      subject: 'Forensic Science',
      title: 'Textbook of Forensic Medicine & Toxicology',
      writer: 'Krishan Vij (Author)',
      edition: '10th',
      image: 'https://images-eu.ssl-images-amazon.com/images/I/51gFrgFcjzL.jpg',
      rating: 3.9,
      description:
          '''Thoroughly revamped and revised edition carrying precise information in a concise manner.
Radical changes have been effected in the chapters Death and Its Medicolegal Aspects: Forensic Thanatology; Sudden and Unexpected Deaths; Asphyxial Deaths; Deaths Associated with Surgery, Anaesthesia and Blood Transfusion; Custody Related Torture and/or Death; Medicolegal Examination of the Living; Injuries by Firearms; Complications of Trauma: Was Wounding Responsible for Death?; Consent to and Refusal of Treatment; Medical Negligence; and Intricacies of Forensic Toxicology.
Enriched with photographs, drawings, sketches, flowcharts, and tables for easy and catchy understanding.
Old cases have been replaced with new ones, making way for the readers to appreciate medicolegal implications.
Reflects author’s personal experience of about three decades and the knowledge gathered from extensive reading, interactions, deliberations, etc. at various platforms.''',
      link:
          'http://93.174.95.29/main/1492000/f27ec4c5a0fb11d01105790a0ad72e6e/Krishen%20Vij%20-%20Textbook%20of%20Forensic%20Medicine%20and%20Toxicology%205E.pdf'),
  Book(
      id: 210,
      subject: 'Forensic Science',
      title:
          'Exam Preparatory Manual for Undergraduates: Forensic Medicine and Toxicology',
      writer: 'V Dekal(Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41-yJ3go3sL._SX355_BO1,204,203,200_.jpg',
      rating: 3.8,
      description:
          '''This book is the first of its kind on the subject. It covers all the aspects of the forensic medicine, namely theory, practical and viva-voce examination and, hence, would satisfy all the needs of an undergraduate student. The contents of the book are prepared in accordance with the syllabus prescribed by the MCI with utmost caution not to miss any single question or point which an undergraduate student is expected to learn in the second year of MBBS course. This book is written in simple language, point by point in a sequential order and, hence very easy to understand recollect and reproduce in the examination and also apply their knowledge more practically in real-time situations as a doctor.''',
      link:
          'http://93.174.95.29/main/2286000/4884e6c8954105ba04afd45a2a800b2b/V%20Dekal%20-%20Exam%20Preparatory%20Manual%20for%20Undergraduates_%20Forensic%20Medicine%20and%20Toxicology-Jaypee%20Brothers%20Medical%20Publishers%20%282015%29.pdf'),
  Book(
      id: 211,
      subject: 'Dermatology',
      title: 'Textbook of Cosmetic Dermatology',
      writer: 'Editors: Robert Baran, Howard Maibach',
      edition: '5th',
      image:
          'https://images.tandf.co.uk/common/jackets/amazon/978148225/9781482257342.jpg',
      rating: 4.2,
      description:
          '''This text documents the science that lies behind the expanding field of cosmetic dermatology so that clinicians can practice with confidence and researchers can be fully aware of the clinical implications of their work. New chapters have been added to this edition on photodamage, actinic keratoses, UV lamps, hidradenitis suppurativa, age-related changes in male skin, changes in female hair with aging, nonabltaive laser rejuvenation, and cryolipolysis, and chapters have been updated throughout to keep this at the forefront of work and practice.

The Series in Cosmetic and Laser Therapy is published in association with the Journal of Cosmetic and Laser Therapy.''',
      link:
          'https://drive.google.com/uc?export=download&id=1QVgcHbYIedE0Z2u1hzHOsEa4A61pC8Xf'),
  Book(
      id: 212,
      subject: 'Dermatology',
      title: 'Andrews\' Diseases of the Skin Clinical Atlas',
      writer:
          'William D. James MD (Author), Dirk Elston MD (Author), Patrick J. McMahon MD (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51LXUf2oVKL._SX389_BO1,204,203,200_.jpg',
      rating: 4.6,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1d1PtVC3nFf2zw3rxxvjGIrUx5aP4T_5p'),
  Book(
      id: 213,
      subject: 'Dermatology',
      title: '100 Cases in Dermatology',
      writer:
          'Rachael Morris-Jones  (Author), Ann-Marie Powell (Author), Emma Benton (Author)',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41RfNKBB8dL._SX351_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1GuMbtkPoxtfnpS9FOPTasA59HWIqw9Ui'),
  Book(
      id: 214,
      subject: 'Dermatology',
      title: 'ABC of Dermatology (ABC Series)',
      writer: 'Rachael Morris-Jones (Editor)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51HHuHaa5dL._SX395_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1xpE9as8_mXbqRZA8XlogLKmr2wUuIrp4'),
  Book(
      id: 215,
      subject: 'Dermatology',
      title: 'Clinical Dermatology',
      writer: 'John C. Hunter (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41jaxAXwnOL._SX380_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1pyxluIYDnZwUZStFfNNLlIwqmxvesF1B'),
  Book(
      id: 216,
      subject: 'Dermatology',
      title: 'Fitzpatrick\'s Dermatology in General Medicine',
      writer: 'Irwin M. Freedberg (Editor), Thomas B. Fitzpatrick (Editor)',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/510TRG4WM0L._SX344_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1SKrLgeKSPnmu3ARLPnmAdKbdXVsqwDPz'),
  Book(
      id: 217,
      subject: 'Dermatology',
      title: 'Review of Dermatology',
      writer: 'Alikhan MD, Ali (Author), Hocker MD MPhil, Thomas L.H  (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41vmjJPMxKL._SX389_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Comprehensive in scope, easy to use, and aligned to the texts you trust, Review of Dermatology, edited by Drs. Ali Alikhan and Thomas L.H. Hocker, is a highly effective study tool for your upcoming board or maintenance exam. Using a concise, bullet-point format and mnemonic devices throughout, this unique guide ensures rapid and efficient recall of the information you need to know for exam success!

Covers all sub-specialty areas, including general dermatology, dermatopathology, pediatrics, pharmacology, basic science, and dermatologic surgery.
Maximizes retention and recall by using an outline approach, bullet points, and mnemonic devices that clearly identify key information.
Illustrates and simplifies complex concepts with more than 400 high-quality clinical images, tables, illustrations, and histopathology slides.
Keeps you up-to-date with the latest hot-topic developments including new biologic agents used in the treatment of various diseases such as psoriasis, eczema and melanoma.
Reviews topics you won’t find in any other dermatology study guide, such as genetic alterations and molecular laboratory studies in melanocytic lesions, soft tissue tumors, and other neoplasms.
Helps you recognize the often-elusive associations between skin diseases and disorders of other organ systems.
Expert Consult™ eBook version included with purchase. This enhanced eBook experience allows you to search all of the text, figures, and references from the book on a variety of devices.''',
      link:
          'https://drive.google.com/uc?export=download&id=1-B7dKD6SRGLciCRrJZapO9C2kwd7XTIr'),
  Book(
      id: 218,
      subject: 'Dermatology',
      title:
          'Illustrated Synopsis Of Dermatology and Sexually Transmitted Diseases',
      writer: 'Neena Khanna',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51rbIU5Ew-L._SX387_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''Illustrated Synopsis of Dermatology and Sexually Transmitted Diseases is a simplified and brief journey through skin diseases, peppered with numerous clinical pictures, illustrations and tables. The main aim of this book is to familiarize the medical student and the general practitioner with the plethora of common skin conditions he is likely to encounter, how to handle them correctly and not to succumb to the morbid temptation of prescribing steroids.''',
      link:
          'http://booksdl.org/get.php?md5=1d6891ee93f4a6a2b4614a8660b5aa8e&key=J2HEF5O2K90Z8MB2'),
  Book(
      id: 219,
      subject: 'ENT',
      title: 'Diseases of Ear, Nose and Throat',
      writer: 'P L Dhingra (Author), Shruti Dhingra (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51fp6hYcIbL._SX385_BO1,204,203,200_.jpg',
      rating: 4.5,
      description: '''The present edition is revised, updated and expanded.
Several new clinical photographs, diagrams, tables and
fl owcharts have been added to make the subject clear. A
unique feature of this edition is white board lectures and
videos, depicting through animations, the surgical
procedures.
The present edition is revised, updated and expanded. Several new clinical photographs, diagrams, tables and fl owcharts have been added to make the subject clear. A unique feature of this edition is white board lectures and videos, depicting through animations, the surgical procedures.''',
      link:
          'https://drive.google.com/uc?export=download&id=1G-7DA2eOZ8RUYA3u_lDN46lufF0nH-Id'),
  Book(
      id: 220,
      subject: 'ENT',
      title: 'Clinical Methods in Ent',
      writer: 'P. T. Wakode  (Author)',
      edition: '1ST',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41WRRK26FYL._SX378_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''A beautifully illustrated monograph with 163 color photographs, is one of the very few books to focus on the ENT patient in clinical methods.''',
      link:
          'https://drive.google.com/uc?export=download&id=12NOMswH0oxSEXmT3ai1JCZYnO1DvsNbV'),
  Book(
      id: 221,
      subject: 'ENT',
      title: 'Textbook of Ear, Nose and Throat Diseases',
      writer:
          'Mohammad Maqbool (Editor), Suhail Maqbool (Editor), Suresh C. Sharma (Foreword)',
      edition: '11th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Cay2%2Bi57L._SX362_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''this textbook has been fully revised to present undergraduates and ENT trainees with the most recent advances in the diagnosis and treatment of ear, nose and throat diseases.

Organised by anatomical region, each section begins with anatomy and physiology then covers the investigation, diagnosis and management of related diseases and disorders. Each section includes multiple choice questions (MCQs) for self assessment.

This new edition includes many new illustrations, as well as additional chapters on neck masses, chemotherapy for head or neck tumours, otolaryngologic concerns in syndromal children, and histopathology of common ENT diseases.''',
      link:
          'https://drive.google.com/uc?export=download&id=1glFO7EcrYowfD2uUNnVvP7yOmD-vbxdF'),
  Book(
      id: 222,
      subject: 'ENT',
      title: 'Self Assesment Review ENT',
      writer: 'Arora Sakshi (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51xGIPw1bnL._SY498_BO1,204,203,200_.jpg',
      rating: 4.6,
      description: '''Salient Features:

Thoroughly revised and updated edition including latest exam pattern questions and image based questions.
Contains lucid presentation of text in a new layout.
Includes recent AIIMS and PGI questions (2013).
Includes DNB, FMGE and NEET pattern questions.
Hot topic Snoring and Sleep Apnea is included.
Color plates with all important illustrations and instruments are given in a separate Section.
All references are from Dhingra 6th edition.
New tables and flow charts have been added.
Must-read for undergraduates, foreign medical graduates, interns, and postgraduate medical aspirants''',
      link:
          'https://drive.google.com/uc?export=download&id=1nflfV4b4nq4ejyrmWZYmZLzRj3zSJJin'),
  Book(
      id: 223,
      subject: 'ENT',
      title: 'Ear, Nose and Throat at a Glance',
      writer: 'Nazia Munir  (Author), Ray Clarke (Author)',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51d8CgnFzuL._SX394_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''Ear, Nose and Throat at a Glance provides a highly-illustrated, accessible introduction to this practical but complex topic, which is increasingly encountered in every-day outpatient settings, as well as surgical departments. Each double-page spread diagrammatically summarises the basic science relating to each anatomical area, outlines practical guidelines on the examination of patients, and provides an overview of the most common disorders and diseases. This brand new title in the best-selling at a Glance series features high-yield information on all the topics covered at medical school, and includes: * Advice on clinical skills, practical examinations and procedures, such as otoscopic examinations, and tuning fork tests * Comprehensive illustrations showing anatomy and mechanisms of hearing * Assessment, management and treatment of both chronic and acute conditions * ENT trauma and emergencies * Multiple Choice Questions (MCQs) and Extended Matching Questions (EMQs) to help test learning Ear, Nose and Throat at a Glance is the ideal companion for anyone about to start the ENT attachment, or special senses rotation, and will appeal to medical students and junior doctors, as well as nurses, audiologists and other health professionals.''',
      link:
          'https://drive.google.com/uc?export=download&id=1LnahYlgJnGpOaYZO6BfzXuaa2wb7NJpM'),
  Book(
      id: 224,
      subject: 'ENT',
      title: 'Color Atlas of ENT Diagnosis',
      writer: 'Tony R. Bull (Author), John S. Almeyda (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51LMD2HLAJL._SX332_BO1,204,203,200_.jpg',
      rating: 3.8,
      description:
          '''Returning in a new edition, this popular color atlas is a concise visual guide for the diagnosis of the full range of ENT conditions. Incorporating the latest developments in the field, this edition opens with an overview of examination techniques, providing descriptions of instruments, imaging, and diagnostic tests. Separate sections cover common and uncommon disorders of the ear, nose, pharynx and larynx, and the head and neck. High-quality photographs are complemented by guidelines for the effective diagnosis and treatment of each clinical problem.''',
      link:
          'https://drive.google.com/uc?export=download&id=1nflfV4b4nq4ejyrmWZYmZLzRj3zSJJin'),
  Book(
      id: 225,
      subject: 'ENT',
      title: 'ABC of Ear, Nose and Throat',
      writer: 'Harold S. Ludman (Editor), Patrick J. Bradley (Editor)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41Xrw8dVcjL._SX395_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''ABC of Ear, Nose and Throat is a long established best-selling guide to the management of common conditions of the Ears, Nose and Throat. It follows a symptomatic approach for evaluation and prioritisation of common presentations, and provides guidance on primary care assessment and management, and on when and why to refer for a specialist opinion.

Fully revised to reflect the current practice of oto-rhino-laryngology and head and neck surgery, new chapters address the increasing specialization and improved understanding of the likely causes and specialist treatment for symptoms such as tinnitus, nasal discharge, nasal obstruction, facial plastic surgery, head and neck trauma and foreign bodies, and non-specialist assessment and examination. There is new content on rhinoplasty, pinnaplasty, non-melanoma skin tumours, thyroid disease and head and neck cancer, with many new full colour illustrations and algorithms throughout.

This title is also available as a mobile App from MedHand Mobile Libraries. Buy it now from iTunes, Google Play or the MedHand Store.''',
      link:
          'https://drive.google.com/uc?export=download&id=1dzW01sjURv3oF6TBFe8xvydbP6LP70QT'),
  Book(
      id: 226,
      subject: 'ENT',
      title: 'Multiple Choice Questions in ENT',
      writer: 'P.L. Dhingra (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/419BATaimwL._SX319_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''The purpose of this book is to guide students in answering MCQs which are a part of examination in various universities, postgraduate entrance tests and other competitive examinations.''',
      link:
          'https://drive.google.com/uc?export=download&id=1nflfV4b4nq4ejyrmWZYmZLzRj3zSJJin'),
  Book(
      id: 227,
      subject: 'Ophthalmology',
      title: 'Kanski\'s Clinical Ophthalmology : A Systematic Approach',
      writer: 'Jogi Renu (Author)',
      edition: '8th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41SY9P6-JOL._SX389_BO1,204,203,200_.jpg',
      rating: 3.7,
      description:
          '''Kanskis Clinical Ophthalmology: A Systematic Approach is the classic specialty text providing the perfect ophthalmology foundation for trainees through to experienced practitioners. The famous visually dynamic and succinct format enables easy comprehension and focused guidance in the diagnosis and management of ophthalmic disorders.''',
      link:
          'http://93.174.95.29/main/1360000/1afe99fafd81b5ba3b3e14240054b3aa/Brad%20Bowling%20FRCSEd%28Ophth%29%20%20FRCOphth%20%20FRANZCO%20-%20Kanski%27s%20Clinical%20Ophthalmology_%20A%20Systematic%20Approach%2C%208e-Saunders%20Ltd.%20%282015%29.pdf'),
  Book(
      id: 228,
      subject: 'Ophthalmology',
      title: 'Comprehensive Ophthalmology',
      writer:
          'AK Khurana (Author), Aruj K Khurana (Author), Khurana Bhawna (Author)',
      edition: '6th',
      image:
          'https://images-eu.ssl-images-amazon.com/images/I/51cSx8rj%2BXL.jpg',
      rating: 3.6,
      description:
          '''The Comprehensive Ophthalmology is primarily meant for the needs of undergraduate medical students. Text is complete and up-to-date with recent advances. To be true, some part of the text is in more detail than the requirement of undergraduate students. But this very feature of the book makes it a useful handbook for the postgraduate students as well. Text is illustrated with plenty of diagrams, comprising clinical photographs and clear-line diagrams which provide vivid and lucid details. Operative steps of important surgical techniques have been given in the relevant chapters. Wherever possible, important information has been given in the form of tables and flow charts. This book has been organized into six sections, including Anatomy and Physiology of Eye, Optics and Refraction, Diseases of Eye, Ocular Therapeutics, Systemic and Community Ophthalmology and Practical Ophthalmology.''',
      link:
          'https://drive.google.com/uc?export=download&id=13KkR2F73ZwkfQGafFh9jadPOUOAk5H87'),
  Book(
      id: 229,
      subject: 'Ophthalmology',
      title: 'Review Questions in Ophthalmology',
      writer: 'Kenneth C. Chern MD (Editor), Michael A. Saidel MD (Editor)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51QB0CkxYkL._SX421_BO1,204,203,200_.jpg',
      rating: 3.8,
      description:
          '''Approach your exams with confidence using Review Questions in Ophthalmology , Third Edition. You’ll find a concise review of all specialty rotations in ophthalmology, plus key areas such as embryology, anatomy, pediatrics, plastics, and lenses. Real-life clinical cases and more than 1,000 multiple choice questions with answers and explanations in this comprehensive review of ophthalmology provide core knowledge for all residents and fellows in ophthalmology, preparing you for success – both on your exams and in your practice!''',
      link:
          'https://drive.google.com/uc?export=download&id=1ODccEiLMym00VsqJ8sK22_xOZTttvWy9'),
  Book(
      id: 230,
      subject: 'Ophthalmology',
      title:
          'The Wills Eye Manual: Office and Emergency Room Diagnosis and Treatment of Eye Disease',
      writer:
          'Gerstenblith MD, Adam T. (Author), Rabinowitz MD, Michael P. (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51rrbkcrXUL._SX331_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''Completely revised, this 6th edition of The Wills Eye Manual: Office And Emergency Room Diagnosis And Treatment Of Eye Disease is the perfect guide for all clinicians who treat eye disorders.

Written in a concise outline format, this easy-to-read, pocket-sized reference is perfect for diagnosis and management of hundreds of ocular conditions. From symptom to treatment it covers every ocular disorder likely to be encountered in an office, emergency room, or hospital setting.

Yet even though it’s small enough to fit in a pocket, this book provides the most accurate and current information on over 200 ophthalmic conditions.  It even includes the results of some of the most recent major clinical trials — including those related to the care of patients with macular degeneration and retinal vein occlusion.

 

NEW TO THE SIXTH EDITION:

·       Chapters thoroughly updated and streamlined to make room for new and expanded topics

·       Recent major clinical trials data included on care of patients with macular degeneration and retinal vein occlusion

·       Updates in the management of orbital fractures, eyelid lacerations, strabismus, amblyopia, and ocular malignancies

·       New high definition photographs of external, anterior segment, and posterior segment disease processes 

·       Imaging modalities updated, especially optical coherence tomography, magnetic resonance imaging, computed tomography, and ultrasound           biomicroscopy''',
      link:
          'https://drive.google.com/uc?export=download&id=136wQq_HTnFnuNEvN5ID6Ao2XYaxbLluQ'),
  Book(
      id: 231,
      subject: 'Ophthalmology',
      title: 'Handbook Of Clinical Trials In Ophthalmology',
      writer: 'Gupta Ak (Author)',
      edition: 'Paperback – 2014',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51%2B%2BA3ddyuL._SX331_BO1,204,203,200_.jpg',
      rating: 3.0,
      description:
          '''It is important for ophthalmologists to keep up to date with the most recent research and advances in their rapidly developing field. This handbook is a compilation of major clinical trials in different subspecialties in the field of ophthalmology. Each trial is presented in a uniform manner, detailing the background and purpose of the study, design, number of subjects with inclusion and exclusion criteria, outcomes, then results and conclusions. Key points Compilation of major clinical trials in ophthalmology Covers all subspecialties in the field Each trial is presented in a uniform manner to assist learning Includes extensive references for further reading''',
      link:
          'https://drive.google.com/uc?export=download&id=1H690LRxdDiLuV2clzj9kgoa7MtaGgmSz'),
  Book(
      id: 232,
      subject: 'Ophthalmology',
      title: 'Wills Eye Handbook of Ocular Genetics',
      writer:
          'Alex Levin (Author), Mario Zanolli (Author), Jenina Capasso (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41xf%2BdlGTHL._SX332_BO1,204,203,200_.jpg',
      rating: 3.0,
      description:
          '''Many serious, potentially blinding eye disorders have a genetic basis. Currently, there are relatively few ocular geneticists in the world, yet inherited eye disease is one of the leading causes of blindness worldwide. Significant strides have been made in gene identification and acquisition of knowledge on the underlying mechanisms of hereditary eye disease. The field of ocular genetics is becoming an increasingly relevant part of ophthalmologists\' purview. This has resulted in a dire need for a comprehensive textbook ophthalmologists and other professionals who work with patients with genetic disorders can utilize to gain a better understanding of inherited eye disorders.

The Wills Eye Handbook of Ocular Genetics, by Alex Levin, Mario Zanolli, and Jenina Capasso of Wills Eye Hospital, is a practical, reader-friendly guide on the diagnosis and management of ophthalmic genetic conditions. Every chapter begins with a disease overview, followed by relevant modern genetic concepts, pathways to attaining the correct diagnosis, and pitfalls and pearls gleaned from years of hands-on expertise. At the end of each chapter, questions and answers enable readers to test their knowledge in real-life scenarios they might face in everyday practice. The ultimate goal of this clinically robust handbook is to facilitate optimal patient management and outcomes.

Key Features

Fundamentals, including basic genetics, inheritance patterns, genetic testing, and ethical issues
Patient-centered genetic counseling issues such as reproduction, dealing with emotional reactions, prognosis, and future options
Anterior segment disorders - from corneal dystrophies and aniridia - to childhood cataract and microphthalmia
A broad spectrum of vitreoretinopathies and retinal diseases including incontinentia pigmenti, retinitis pigmentosa, Bardet-Biedl syndrome, choroideremia, Stargardt disease, achromatopsia, and juvenile X-linked retinoschisis
This textbook is essential reading for practitioners at all levels and in all subspecialties including ophthalmology and genetics. They will find it an excellent resource for navigating the complexities of genetic eye disease.''',
      link:
          'https://drive.google.com/uc?export=download&id=1it1iASJG2AC7p77TRJ2fbfucQXO5blfm'),
  Book(
      id: 233,
      subject: 'Ophthalmology',
      title: 'Handbook of Emergency Ophthalmology',
      writer: 'Brit Long (Editor), Alex Koyfman (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/411t1GWvS6L._SX316_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''This book provides emergency physicians with an easy-to-use guide for diagnosing and treating ophthalmologic conditions in the emergency department. Ophthalmologic complaints are very common, but many emergency physicians are not as confident as they would like to be when evaluating and managing these conditions. This book answers that need by giving step-by-step instructions on how to diagnose and treat common eye conditions, including glaucoma, infections, neuro-ophthalmologic conditions, and trauma. For each disorder, the book discusses presentation/symptoms, physical examination techniques, lab and imaging findings, differential diagnoses, treatment guidelines, and referral suggestions. The text is filled with images that clearly present these common ophthalmologic complaints and conditions and guide the emergency physician to an accurate and swift diagnosis. Handbook of Emergency Ophthalmology is an essential resource for emergency physicians, residents, medical students, nurses, and other healthcare workers who evaluate and manage patients with ophthalmologic conditions.''',
      link:
          'https://drive.google.com/uc?export=download&id=1h2W_JZmzett07U6MRpOhA2LFk0A4F91b'),
  Book(
      id: 234,
      subject: 'Ophthalmology',
      title:
          'Oxford American Handbook of Ophthalmology (Oxford American Handbooks of Medicine)',
      writer:
          'James Tsai, Alastair Denniston, Philip Murray, John Huang, Tamir Aldad',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41u%2BIf74YbL._SX279_BO1,204,203,200_.jpg',
      rating: 4.0,
      description:
          '''In a concise and contemporary new edition, the Oxford American Handbook of Ophthalmology offers highly practical yet evidence-based guidance on the diagnosis and management of ophthalmic disorders. Incorporating a systematic approach, the authors present common and/or important manifestations of the full spectrum of eye diseases. Included are useful summaries of common signs and symptoms, etiologies, diagnostic testing, and therapeutic regimens, as well as information on pre-, peri-, and post-operative eye care. The Oxford American Handbook should prove useful and relevant to residents and fellows in ophthalmology, as well as medical students, primary care physicians, comprehensive ophthalmologists, and other ophthalmic personnel, all who seek a ready reference for daily clinical practice and review.''',
      link:
          'http://93.174.95.29/main/612000/59b9eb7a1f88af13010dafd3ea40f8bd/%28Oxford%20American%20Handbooks%20in%20Medicine%20one%20volume%29%20James%20Tsai%2C%20Alastair%20Denniston%2C%20Philip%20Murray%2C%20John%20Huang%2C%20Tamir%20Aldad%20-%20Oxford%20American%20Handbook%20of%20Ophthalmology%20%28Oxford%20American%20Handbooks%20in%20Medi.pdf'),
  Book(
      id: 235,
      subject: 'Ophthalmology',
      title: 'Ophthalmology at a Glance',
      writer: 'Jane Olver  (Author), Lorraine Cassidy (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51TsfpYXfTL._SX394_BO1,204,203,200_.jpg',
      rating: 3.8,
      description:
          '''"Ophthalmology at a Glance" is a concise textbook written as part of the highly successful at a "Glance Series". The book follows the classic format of topics laid out in a double page spread, with clear diagrams illustrating the essential information and supporting the main text. This makes learning and understanding a topic more simple and effective. "Ophthalmology at a Glance" is written to provide a straightforward and easy-to-use guide for the Ophthalmology course. The introduction includes an overview of the subject and it\'s sub-specialities, an outline of what exact knowledge and skills medical students need, and covers the social and occupational aspects of vision. History and Examination techniques are followed by the key detail on common problems and diseases. The book is divided into 13 sections covering: Principles of ophthalmology; Ophthalmic History and Examination; Correction of Refractive errors; Basic Eye Examination; Acute ophthalmology; Gradual loss of vision; Paediatric ophthalmology; Eyelid, lacrimal and orbit; External eye disease; Corneal, refractive and cataract surgery; Glaucoma; Vitreo-retinal; and, Neuro-ophthalmology. "Ophthalmology at a Glance" will be extremely useful for medical students as an introduction to this subject area, and an invaluable companion during their attachments. This book is designed to fit into the budget and reading time of busy students, and is ideal as a text that will help them get through their exams successfully. General Practitioners and ophthalmology nurses will also find this text useful to refresh the gaps in their knowledge. \'This is undoubtedly the best I have read and I wish it had been available when I studied ophthalmology. It is clear, concise, and pitched perfectly for medical students\' - Final year medical student (Royal Free Hospital, London).''',
      link:
          'https://drive.google.com/uc?export=download&id=1vnpcfEHIMsC_fHXZZISB4F9ursx63nV9'),
  Book(
      id: 236,
      subject: 'Ophthalmology',
      title: 'AK Khurana Review of Ophthalmology',
      writer: 'AK Khurana(Author)',
      edition: '6th',
      image:
          'https://medbook4u.com/wp-content/uploads/2018/10/revophkhu6th.jpg',
      rating: 0.0,
      description:
          '''Keeping in view the requirements of the students for a ready-made material for various postgraduate entrance examinations the Comprehensive Ophthalmology is accompanied with Review of Ophthalmology.

Review of Ophthalmology provides a means of quick revision and self assessment to the medical students.

It has been organized into two sections of twenty chapters each.''',
      link:
          'https://drive.google.com/uc?export=download&id=1yMNPFsgkHVONpqQ_pdjFjb1F5zp1Gfx-'),
  Book(
      id: 237,
      subject: 'Ophthalmology',
      title: 'Ocular Disease: Mechanisms and Management',
      writer:
          'Levin MD PhD, Leonard A (Author), Albert MD MS, Daniel M. (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51C5140C4vL._SX395_BO1,204,203,200_.jpg',
      rating: 3.7,
      description:
          '''Ocular Disease―a newly introduced companion volume to the classic Adler’s Physiology of the Eye―correlates basic science and clinical management to describe the how and why of eye disease processes and the related best management protocols. Editors Leonard A. Levin and Daniel M. Albert―two of the world’s leading ophthalmic clinician-scientists―have recruited as contributors the most expert and experienced authorities available in each of the major areas of ophthalmic disease specific to ophthalmology: retina, cornea, cataract, glaucoma, uveitis, and more. The concise chapter structure features liberal use of color―with 330 full-color line artworks, call-out boxes, summaries, and schematics for easy navigation and understanding. In print and online at expertconsult.com, this comprehensive resource provides you with a better and more practical understanding of the science behind eye disease and its relation to treatment.

Includes access to the fully searchable text online at expertconsult.com, along with images and references.
Covers all areas of disease in ophthalmology including retina, cornea, cataract, glaucoma, and uveitis for the comprehensive information you need for managing clinical cases.
Presents a unique and pragmatic blend of necessary basic science and clinical application to serve as a clinical guide to understanding the cause and rational management of ocular disease.
Features 330 full-color line artworks that translate difficult concepts and discussions into concise schematics for improved understanding and comprehension.
Provides the expert advice of internationally recognized editors with over 40 years of experience together with a group of world class contributors in basic science and clinical ophthalmology.
Your purchase entitles you to access the web site until the next edition is published, or until the current edition is no longer offered for sale by Elsevier, whichever occurs first. Elsevier reserves the right to offer a suitable replacement product (such as a downloadable or CD-ROM-based electronic version) should access to the web site be discontinued. Registration and use of the web site is subject to the terms of the non-transferable, limited license under which access to the site and its content is granted by Elsevier. Access to the site by individuals is limited to the first retail purchaser and may not be transferred to another party by resale, lending or other means.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Lu7wzvxuTRWClYEycRxrqjAEVrG2CmDC'),
  Book(
      id: 238,
      subject: 'Ophthalmology',
      title:
          'Basic Sciences for Ophthalmology (Oxford Specialty Training: Basic Science)',
      writer:
          'Louise Bye (Author), Neil Modi (Author), Miles Stanford (Author)',
      edition: 'Paperback – 23 May 2013',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51hBuVeQEFL._SX380_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''Part of the Oxford Specialty Training series, Basic Sciences for Ophthalmology is an indispensable and fully comprehensive textbook, and the only book candidates will need to pass the FRCOphth Part 1 exam. Directly linked to the Royal College\'s exam, presented in a full colour, highly illustrated, and easy-to-read format, making the basic science behind ophthalmology more approachable and accessible to improve understanding.

Offering full coverage of the Royal College curriculum, the book includes information on anatomy, physiology, biochemistry, and optics. Useful as a resource for the basic sciences in ophthalmology, the book will be also of interest to senior trainees, consultants, optometrists, orthoptists, and basic scientists, as well as those taking the FRCOphth exams.''',
      link:
          'https://drive.google.com/uc?export=download&id=1gATraH1n9UFUDbEbnr487OBE5ucbKIzV'),
  Book(
      id: 239,
      subject: 'Ophthalmology',
      title: 'SPEC - Ophthalmology',
      writer: 'Myron Yanoff (Author), Jay S. Duker (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51BROBQ7v%2BL._SX495_BO1,204,203,200_.jpg',
      rating: 4.0,
      description:
          '''Long considered one of ophthalmology’s premier texts, this award-winning title by Drs. Myron Yanoff and Jay S. Duker remains your go-to reference for virtually any topic in this fast-changing field. It offers detailed, superbly illustrated guidance on nearly every ophthalmic condition and procedure you may encounter, making it a must-have resource no matter what your level of experience. Extensive updates throughout keep you current with all that’s new in every subspecialty area of the field.''',
      link:
          'https://drive.google.com/uc?export=download&id=1C-YCxdcyb3NyFg7mEW03_Tvl0d9vqsMG'),
  Book(
      id: 240,
      subject: 'Ophthalmology',
      title: 'Clinical Procedures for Ocular Examination, Fourth Edition',
      writer: 'Nancy B. Carlson (Author), Daniel Kurtz (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/518fgRcWwzL._SX330_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''Clinical Procedures for Ocular Examination, Fourth Edition is the must-have eye care resource, whether you’re a student, resident, or practitioner. Here, in one concise handbook, is every major clinical procedure used in ocular examinations. Offering ideal preparation for clinical eye exams, the book features detailed, systematic guidance on how to confidently perform all major examination techniques, which are described by purpose, indication, equipment, set-up, recording, and examples.

Each procedure is accompanied by precise illustrations and photographs, designed to enhance your knowledge and comfort level with the full spectrum of techniques. Clinical Procedures for Ocular Examination, Fourth Edition represents the single most essential clinical companion in eye care available anywhere.

Step-by-step procedures for every exam procedure, including techniques that are new to this edition
Convenient summaries of practical how’s and why’s that do not get bogged down in distracting theory
Expanded tables, plus updated references and norms''',
      link:
          'https://drive.google.com/uc?export=download&id=1uU3zIN2TF_P5_xzhRXncLpDjeV8BM0iO'),
  Book(
      id: 241,
      subject: 'Ophthalmology',
      title: 'Review of Ophthalmology',
      writer: 'Authors: Neil Friedman Peter Kaiser William Trattler',
      edition: '3rd',
      image:
          'https://secure-ecsd.elsevier.com/covers/80/Tango2/large/9780323390569.jpg',
      rating: 3.7,
      description:
          '''Designed to maximize easy retention and quick recall, Review of Ophthalmology, 3rd Edition, by Drs. Neil J. Friedman, Peter K. Kaiser, and William B. Trattler, is the best-selling review book you can trust to get you successfully through your exams. An efficient, easy-to-digest format distills key information into highly relevant bullet points. You’ll quickly master what you need to know in all subspecialty areas, including the latest information on today’s standard diagnostic techniques, medical treatments, and surgical options.''',
      link:
          'https://drive.google.com/uc?export=download&id=1wTx0x5ugeHIhocK9zis1QbPTC-rOCNLP'),
  Book(
      id: 242,
      subject: 'Ophthalmology',
      title: 'Parson\'s Diseases of the Eye',
      writer:
          'Sihota (Author), Tandon MBBS MD DipNB FRCOphth FRCS, Radhika (Author)',
      edition: '22th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/414SHPwmBFL._SX380_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''A trusted textbook for undergraduate students for more than 100 years, which also caters to the basic needs of postgraduate students and practitioners.
 
The book was first published in 1907, and on account of its clear and friendly presentation style as well as its authoritative coverage of ocular disorders, it quickly became a fundamental text for students. Since then the book has maintained its popularity with students through regular revisions and updates.
 
The 19th edition of this book was especially adapted to the context of Indian subcontinent with a special mention about the infections that occur predominantly in this region. The 22nd edition continues this trend by presenting unparalleled guidance on nearly every ophthalmic condition and procedure, including the latest advances in the field, making the book more comprehensive and contemporary.

• Inclusion of Important Points to Remember at the end of the book
• Addition of new clinical photographs, flowcharts, and tables to facilitate quick learning
• Extensively revised and updated edition
• Reader-friendly version with information highlighted in points, flow charts and tables
• Information provided to help prepare for PG entrance and other competitive examinations''',
      link:
          'https://drive.google.com/uc?export=download&id=1fSGpHLbezygdxp511uEJ9cBA2bitXvTB'),
  Book(
      id: 243,
      subject: 'Ophthalmology',
      title: 'Self Assessment and Review of Ophthalmology (PGMEE)',
      writer: 'Sudha Seetharam (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Aer63CyuL._SX351_BO1,204,203,200_.jpg',
      rating: 4.2,
      description: '''• Golden points for NEET added at the end of each chapter

• Concise text referenced from Clinical Ophthalmology: Kanski, Ophthalmology: Yanoff-Duker and

Comprehensive Ophthalmology: AK Khurana

• Important points to remember have been highlighted with superscript Q

• Collection of representative recent MCQs from AIIMS/AIPG/PGI/COMEDK/DNB and State PG entrance examinations

      This atlas is a pocket manual of imaging diagnosis of the orbital. It includes common imaging techniques, normal imaging features, abnormal orbital imaging of developmental diseases, injury, inflammation, lymphoproliferative diseases, diseases of the eyeball, post-operative changes, vascular diseases, tumors and neuro-ophthalmological diseases. While it particularly focuses on CT and MRI, it also describes other techniques, such as X-ray, ultrasonography and nuclear imaging. The book starts with an overview of commonly used imaging techniques of the orbit a concise description of imaging features of normal orbit in X-ray, CT and MRI. The following nine chapters explore different orbital diseases and abnormalities that are common in clinical work. It is a valuable resource for radiologists and ophthalmologists.''',
      link:
          'https://drive.google.com/uc?export=download&id=120Q4_8CvohF5hfQuYIkAvfdIyVaFueSJ'),
  Book(
      id: 244,
      subject: 'Ophthalmology',
      title: 'Postgraduate Ophthalmology - Vol.2',
      writer:
          'Zia Chaudhuri (Author), Zia Chaudhari (Editor), Murugesan Vanathi (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Rhk%2BrBj9L._SX427_BO1,204,203,200_.jpg',
      rating: 1.0,
      description:
          '''This well-illustrated two volume set covers the field of ophthalmology, from the fundamentals to the most recent advances. Each section is dedicated to a specific area of the eye and covers basic techniques, investigative modules and treatment methods. With the help of 2500 images and illustrations, this book covers topics such as glaucoma, ocular oncology, nystagmus, refractive surgery, strabismus and lasers in ophthalmology. Low vision, medico-legal aspects, operating room sterilisation and ocular emergencies are also discussed.''',
      link:
          'https://drive.google.com/uc?export=download&id=1_uNR8G1Fr6bG4jooWmy1gdjHY95G2hwY'),
  Book(
      id: 245,
      subject: 'Ophthalmology',
      title: 'MCQs-in-Ophthalmology',
      writer: '',
      edition: '',
      image:
          'https://cdn.prometricmcq.com/wp-content/uploads/2018/07/Ophthalmology-MCQs-400x400.gif',
      rating: 5.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1QGu0RlzQRJR3QxcuauJs39JaYYBHdLKo'),
  Book(
      id: 246,
      subject: 'Orthopaedic',
      title: 'The Handbook of Fracture',
      writer:
          'Kenneth Egol MD (Editor), Kenneth J. Koval MD (Editor), Joseph Zuckerman MD (Editor)',
      edition: '4th',
      image:
          'https://www.medgag.com/wp-content/uploads/2018/10/Screenshot_2018_1030_192913-639x1024.png',
      rating: 4.5,
      description:
          '''One of the most widely used manuals of its kind, Handbook of Fractures, 5th Edition , is the ideal, on-the-spot reference for residents and practitioners seeking fast facts on fracture management and classification. Carry it with you for convenient access to the answers you need on complete fracture care of adults and children – from anatomy and mechanism of injury through clinical and radiologic evaluation and treatment.
Key Features
Visualize key aspects of fracture management with abundant illustrations.
Access vital information through quick-reference charts, tables, diagrams, and bulleted lists.
Stay up to date with what’s new in the field thanks to new chapters on intraoperative imaging and basic science of fracture healing.
Get the latest information on special topics such as multiple trauma, gunshot wounds, pathologic and periprosthetic fractures, and orthopedic analgesia.
Quickly find the information you need with consistently organized chapters covering epidemiology, anatomy, mechanism of injury, clinical evaluation, radiologic evaluation, classification, treatment, and management of complications.
Now with the print edition, enjoy the bundled interactive eBook edition, offering tablet, smartphone, or online access to:
Complete content with enhanced navigation .
Powerful search tools and smart navigation cross-links that pull results from content in the book, your notes, and even the web.
Cross-linked pages, references, and more for easy navigation.
Highlighting tool for easier reference of key content throughout the text.
Ability to take and share notes with friends and colleagues.
Quick reference tabbing to save your favorite content for future use.''',
      link:
          'https://drive.google.com/uc?export=download&id=1yOe3Mx45F2i8-SZDKhxLSrOnOydCiYYY'),
  Book(
      id: 247,
      subject: 'Orthopaedic',
      title: 'Textbook of Orthopedics',
      writer: 'John Ebnezar',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51kzcMqzqgL._SX367_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''This book is a comprehensive guide to orthopaedics for postgraduate medical students. The fifth edition has been fully revised to present the latest developments and understanding in the field. The book covers numerous injuries and disorders, with each topic beginning with an overview of relevant anatomy, followed by principles and methods of diagnosis and clinical and surgical management. Each chapter includes a brief summary outlining key points, as well as example X-Rays for the topic in discussion. The fifth edition features new sections on trauma, geriatric orthopaedics, arthroscopy, and surgical techniques, as well as additional images including new X-Rays and MRI scans, and line diagrams. Key Points Comprehensive guide to orthopaedics for postgraduate medical students Fully revised, fifth''',
      link:
          'https://drive.google.com/uc?export=download&id=1Kh0RTsdz7ZlUPBe4mehwOJ0y4_OS7a7p'),
  Book(
      id: 248,
      subject: 'Orthopaedic',
      title: 'HANDBOOK FOR ORTHOPEDICS EXAMINATION THEORY & PRACTICAL',
      writer: 'Kaushik Banerjee (Author), Academic Publishers (Contributor)',
      edition: '6th',
      image:
          'https://www.medgag.com/wp-content/uploads/2018/11/IMG_20181106_135242-728x1024.jpg',
      rating: 4.5,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=10D39vCilBWCg1nf986ETte35JAz7JhcT'),
  Book(
      id: 249,
      subject: 'Orthopaedic',
      title: 'Lecture Notes: Orthopaedics and Fractures',
      writer: '',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41J%2BCd6tUfL._SX350_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1pi5oNANgRjrpwx4EpZNhL0umhUOhkUzk'),
  Book(
      id: 250,
      subject: 'Orthopaedic',
      title: 'Apley\'s System of Orthopaedics and Fractures',
      writer:
          'Louis Solomon (Author), David Warwick (Author), Selvadurai Nayagam (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41789bu9xyL._SX390_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Since the publication of the first edition in 1959, Apley\'s System of Orthopaedics and Fractures has been an essential textbook for those seeking to understand the structure and function of the musculoskeletal system, its diseases and its response to trauma. The book\'s success was initiated by the late Alan Apley\'s skills as a teacher, and the care and forethought that he brought to the presentation of the content.

The current authors have developed and extended this foundation to produce a thoroughly modern textbook of orthopaedic surgery, bringing complementary expertise while retaining the book\'s characteristic philosophy and approach. They are joined by a selection of expert contributors from around the world, who add material on a wide variety of subjects including radiology, open fractures, neuromuscular disorders, and inflammatory arthropathies. 

This 9th edition echoes its predecessors in following Apley\'s approach to the orthopaedic patient. As before, the work is divided ino three section: General Orthopaedics, Regional Orthopaedics, and Fractures and Joint Injuries. The material has been fully updated and revised, including the replacement of the majority of the photographs, giving this edition a modern and relevant feel. The illustrations are all provided in a downloadable form on the book\'s accompanying website.

Apley\'s System\'s wide readership of practicing orthopaedic surgeons, postgraduate trainees and residents in orthopaedics and general surgery, A&E specialists and physiotherapists is evidence of the author\'s ability to instruct and inspire. The book is a trully fitting introduction to modern-day orthopaedics.''',
      link:
          'https://drive.google.com/uc?export=download&id=1ikDBSQ8IIJDt8LRmeoR_FmEZh3H1BN87'),
  Book(
      id: 251,
      subject: 'Orthopaedic',
      title: 'Fundamentals Of Orthopedics',
      writer: 'Mohindra Mukul (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41mJcOoabmL._SX361_BO1,204,203,200_.jpgS',
      rating: 4.1,
      description:
          '''An up-to-date and all-in-one package to tackle theory and practical exams, as well as current entrance exam pattern MCQs.
Elaborative on context of subject material but To-The-Point in description of topics.
Borderline topics in orthopaedics like Spine, Metabolic bone diseases, Arthritis, Skeletal dysplasias, Brachial plexus palsies, Thoracic outket syndrome and Soft tissue sarcomas covered in simplified and complete manner.
Over 900 well labelled images and illustrations depicting all clinical and radiological signs in orthopaedics and the instruments and implants in use.
High yield points given at the end of every topic specially targeting current pattern of MCQs.
Excellent synopsis of all topics at the end of subject.
A smartly prepared Practice Session (over 600 MCQs) covering all possible types of MCQs asked till date in various competitive exams with answer references fro the text.
Picture Quiz based on current trend for practicing image based questions''',
      link:
          'https://drive.google.com/uc?export=download&id=1dAI1Hvazp9HVsfyo8ZkURSmVf227ROlT'),
  Book(
      id: 252,
      subject: 'Psychiatry',
      title: 'Psychiatry (Oxford Medical Publications)',
      writer:
          'John Geddes (Author), Jonathan Price (Author), Rebecca McKnight (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51NnvmTEVqL._SX365_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''Psychiatry introduces medicine students to the subject in a concise, innovative and memorable way. Its patient-centred approach blends a discussion of the theoretical basis of different psychiatric disorders with an explanation of the management of these disorders in everyday clinical practice, using genuine case histories to place the content in a realistic context.

Recognizing that having positive interactions with a patient is central to the provision of successful psychiatric care, the book includes guidance on history-taking and assessment, while also reflecting best practice as set out by current clinical guidelines.

Having undergone an extensive revision for this fourth edition, and covering all the major psychiatric conditions in a logically-structured way, the book is an invaluable guide to all individuals who are likely to encounter those with psychiatric problems, including students of medicine, healthcare, and social work. 

Online Resource Centre
The Online Resource Centre to accompany Psychiatry features 
DT Figures and tables from the book in electronic format
DT Self-assessment materials for students
DT Updates on the latest clinical guidelines''',
      link:
          'https://drive.google.com/uc?export=download&id=1O7TrraizL-aLRxodLaAfhv10K2C2_RXI'),
  Book(
      id: 253,
      subject: 'Radiology',
      title: 'CLARK’S POSITIONING IN RADIOGRAPHY',
      writer:
          'A. Stewart Whitley (Author), Gail Jefferson (Author), Ken Holmes (Author), Charles Sloane (Author), Craig Anderson (Author), Graham Hoadley (Author)',
      edition: '13th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51aX1kH5phL._SX383_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''First published in 1939, Clark’s Positioning in Radiography is the preeminent text on positioning technique for diagnostic radiographers.

Whilst retaining the clear and easy-to-follow structure of the previous edition, the thirteenth edition includes a number of changes and innovations in radiographic technique. The text has been extensively updated, including a new section on evaluating images, The 10-point plan, which is linked throughout to a listing of Essential image characteristics for each procedure. The section on digital imaging has been expanded not only to elaborate more extensively on the technology but to demonstrate its various clinical applications.

New sections also include imaging informatics and its role in the modern world of medical imaging, holistic approaches to patient care and discussion of the important aspect of the patient journey.

Students will also benefit from more detailed reference to positioning errors and how to avoid mistakes, as well as a greater emphasis on standard radiation protection measures and guidance on the most recent radiation dose reference levels for specific examinations.

Clark’s Positioning in Radiography continues to be the definitive work on radiographic technique for all students on radiography courses, radiographers in practice and trainee radiologists.''',
      link:
          'https://drive.google.com/uc?export=download&id=1iDU0bBcke84kxlYGQO-uTB99YRgIeOwF'),
  Book(
      id: 254,
      subject: 'Radiology',
      title: 'Accident and Emergency Radiology: A Survival Guide',
      writer: 'Nigel Raby, Laurence Berman, Simon Morley, Gerald de Lacey',
      edition: '1ST',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41kfBEkWGTL._SX317_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''Since it was first published, Accident and Emergency Radiology: A Survival Guide has become the classic in-my-pocket-reference and an indispensable aid to all those who work in the Emergency Department. The core and substantial value lies in the step-by-step analytical approaches which help you to answer this question: "These images look normal to me, but . . . how can I be sure that I am not missing a subtle but important abnormality?''',
      link:
          'http://93.174.95.29/main/1503000/ada7e86fba9f81b64ad7e5d1cbe6deab/Nigel%20Raby%2C%20Laurence%20Berman%2C%20Simon%20Morley%2C%20Gerald%20de%20Lacey%20-%20Accident%20and%20Emergency%20Radiology_%20A%20Survival%20Guide-Saunders%20%282015%29.pdf'),
  Book(
      id: 255,
      subject: 'Radiology',
      title: 'AIIMS MAMC: PGI’s Comprehensive Textbook of Diagnostic Radiology',
      writer: 'Niranjan Khandelwal, Arun Kumar Gupta, Veena Chowdhury',
      edition: '1ST',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/61HZ7v-Cm8L._SY480_BO1,204,203,200_.jpg',
      rating: 3.3,
      description:
          '''AIIMS MAMC - PGI\'s Comprehensive Textbook of Diagnostic Radiology is an extensive three volume review of conventional and novel imaging techniques for the diagnosis of a wide range of diseases. The first volume of this book covers neuroradiology, including head and neck, recent advances and applied physics in imaging. The second volume covers chest and cardiovascular, gastrointestinal and hepatobiliary, and genitourinary imaging. The final volume covers paediatric imaging, musculoskeletal imaging, including information on imaging for bone, soft tissue and joint diseases, and breast imaging including the role of mammography. AIIMS MAMC - PGI\'s Comprehensive Textbook of Diagnostic Radiology includes discussion on various imaging modalities and the potential for their future use. The book is enhanced by over 6250 images and illustrations, making this an ideal visual resource for radiology residents and practising radiologists. Key Points Three volume review of diagnostic imaging techniques Volumes cover neuroradiology, chest, cardiovascular, gastrointestinal, hepatobiliary, genitourinary, paediatric musculoskeletal, and breast imaging 6254 images and illustrations''',
      link:
          'https://drive.google.com/uc?export=download&id=12KNUgow6pDLixFmErV4XlGZhQEYvMkZT'),
  Book(
      id: 256,
      subject: 'Radiology',
      title: 'Surface And Radiological Anatomy With A Clinical Perspective',
      writer: 'Appaji Ashwini C (Author)',
      edition: '1ST',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51KVkBfM2TL._SX367_BO1,204,203,200_.jpg',
      rating: 4.0,
      description:
          '''• Unique book in the sense that authors have made an effort to emphasize the importance of surface anatomy as well as radiological anatomy in clinical sciences. 
• Helpful in clinical examination, diagnosis and investigation. 
• Diagrams are simple and easily reproducible on the mummified cadaver, on human volunteers and mannequins. 
• Enriched with sketched and photographs in a concise and systematic manner. 
• Applied anatomy boxes to correlate the anatomical structures, differential diagnosis, various surgical methods and clinical features related to them. 
• Provides extensive information regarding the basics of various advanced radiological techniques and procedures, which are simple and easy to understand. 
• Each chapter in Surface Anatomy provides basic concept and information necessary to understand morphology of the structures intended to practice Surface Anatomy. 
• Includes recent advances in the field of Radio diagnosis. 
• Glimpse of modern imaging techniques in addition to conventional radiography to be aware of the importance of cross-sectional Anatomy in Radio diagnosis. 
• Targeted at health professionals, students and clinicians.''',
      link:
          'https://drive.google.com/uc?export=download&id=1n8CFZF_jJoLSHLRNvR0Fmjxt0RCiMgi4'),
  Book(
      id: 257,
      subject: 'Radiology',
      title: 'Clinical Radiology Made Ridiculously Simple',
      writer: 'Hugue Ouellette, Patrice Tetreault',
      edition: '1ST',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51SHYQ99PEL._SX361_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''I love this book so much! It is so much easier to understand than my radiology lectures. They have an amazing was of presenting things in such a way that it really makes you understand and remember them. It also comes with a CD that I thought was very helpful. I often have a hard time diagnosing abnormalities in films and I thought that this book really helped me with that. I would suggest this book for any medical student!''',
      link:
          'http://93.174.95.29/main/2347000/f29d626e819a9feb258792ab53f9817f/Ouellette%2C%20Hugue_%20T%C3%A9treault%2C%20Patrice%20-%20Clinical%20radiology%20made%20ridiculously%20simple-MedMaster%20%282003%29.pdf'),
  Book(
      id: 258,
      subject: 'Radiology',
      title: 'Abdominal Imaging, 2nd Edition Expert Radiology Series',
      writer: 'Dushyant V Sahani, MD and Anthony E Samir, MD, MPH',
      edition: '2ND',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51RUlPMbjcL._SX372_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''Richly illustrated and comprehensive in scope, Abdominal Imaging, 2nd Edition, by Drs. Dushyant V. Sahani and Anthony E. Samir, is your up-to-date, one-volume source for evaluating the full range of diagnostic, therapeutic, and interventional challenges in this fast-changing field. Part of the Expert Radiology series, this highly regarded reference covers all modalities and organ systems in a concise, newly streamlined format for quicker access to common and uncommon findings. Detailed, expert guidance, accompanied by thousands of high-quality digital images, helps you make the most of new technologies and advances in abdominal imaging.''',
      link:
          'https://drive.google.com/uc?export=download&id=1l4VtYos34zg2knZsq8mQRhNfjqBrHYeG'),
  Book(
      id: 259,
      subject: 'Radiology',
      title: 'Grainger & Allison’s Diagnostic Radiology Essentials',
      writer: 'Lee A Grant, Nyree Griffin',
      edition: '2ND',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Ydks1vmpL._SX391_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''Get the quick answers you need on every aspect of diagnostic radiology and apply them in your day-to-day practice. Grainger & Allison’s Diagnostic Radiology Essentials serves as a comprehensive review and reference for radiologists in training and in practice by providing practical solutions to diagnostic problems in the radiological recognition and interpretation of a wide range of disease entities. Organized by body region, its innovative, accessible outline format, bullet point style and numerous, high quality, multi-modality images make essential key facts about any given condition easy to find and retrieve. The content follows the same order and is derived from the renowned authoritative reference work Grainger & Allison’s Diagnostic Radiology. "The authors deserve to be congratulated on their gargantuan efforts and I am sure this textbook will be well thumbed by future radiology trainees preparing for their examinations." RAD Magazine, Nov 2013''',
      link:
          'https://drive.google.com/uc?export=download&id=1tpNNgqLqn7Rl3vMGO11YrLWlyB2zBS8i'),
  Book(
      id: 260,
      subject: 'Radiology',
      title: 'Lecture Notes: Radiology',
      writer: 'Pradip R. Patel (Author)',
      edition: '3RD',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51nMzPHNYvL._SX350_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''Radiology plays an invaluable role in the initial diagnosis and subsequent management of patients and this fully revised and updated new edition of Lecture Notes: Radiology presents the essential core knowledge needed by medical students, junior doctors on the Foundation Programme, specialist nurses and staff in the radiology department.
Organized by body systems, it provides a fundamental understanding of radiology as it focuses on imaging techniques, basic film interpretation, and specialized radiological investigation. It emphasizes the pattern of disease as seen on commonly used X-rays and contrast examinations, with explanatory notes on further investigations by imaging techniques such as ultrasound, CT and MRI.

Lecture Notes: Radiology contains new and updated images and illustrations, an expansion of the skeletal trauma section, \'Key points\' boxes, and increased use of bulleted text, making it ideal for study and revision.''',
      link:
          'https://drive.google.com/uc?export=download&id=1MpMci3UWZIRwmq7Snhiuhj9a-bTRjESF'),
  Book(
      id: 261,
      subject: 'Radiology',
      title: 'Rapid Review of Radiology (Medical Rapid Review Series)',
      writer:
          'Shahid Hussain (Author), Sherif A. A. Latif (Author), Adrian D. Hall (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/5187vKynFIL._SX370_BO1,204,203,200_.jpg',
      rating: 3.7,
      description:
          '''As in all specialties, learning in Radiology is a life long process but in the trainee years there is a vast amount of information to assimilate. In this book the author has compiled a selection of cases covering many aspects of radiology to help trainees with the practical aspects of image recognition and formulating a differential diagnosis. The selection of cases is broad enough to provide an introduction for some readers, with more testing cases for those in the later stages of training. Each self test case is presented with an image, or set of images, together with the pertinent clinical details.
The solution and explanation is presented over the page along with differential diagnoses that logically derive from the images and history. The correct diagnosis is followed by a discussion of the underlying diagnosis with teaching points and main imaging findings, plus any other important factors emerging from the discussion. The book contains 423 images including X rays, ultrasound, CT, MRI, interventional techniques and nuclear medicine. It will be useful to radiologists in training and other health professional wishing to improve their radiological skills.''',
      link:
          'https://drive.google.com/uc?export=download&id=1g37WSTaWyiUo3mlAI1bsNqwr_EZzvLQz'),
  Book(
      id: 262,
      subject: 'Radiology',
      title:
          'AIIMS MAMC: PGI’s Comprehensive Textbook of Diagnostic Radiology | Vol 1-3',
      writer: 'Niranjan Khandelwal, Arun Kumar Gupta, Veena Chowdhury',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/61HZ7v-Cm8L._SY480_BO1,204,203,200_.jpg',
      rating: 5.0,
      description: '''''',
      link:
          'http://93.174.95.29/main/2245000/a5a92dd680eddd5036869d6fe73c1df5/Niranjan%20Khandelwal%2C%20Arun%20Kumar%20Gupta%2C%20Veena%20Chowdhury%20-%20AIIMS%20MAMC_%20PGI%E2%80%99s%20Comprehensive%20Textbook%20of%20Diagnostic%20Radiology.%201-3-Jaypee%20Brothers%20Med.%20Publ.%20%282017%29.pdf'),
  Book(
      id: 263,
      subject: 'Radiology',
      title: 'Review of Radiology (PGMEE)',
      writer: 'Rajat Jain (Author), Virendra Jain (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51f-gIXqAiL._SX363_BO1,204,203,200_.jpg',
      rating: 2.9,
      description:
          '''Image-based learning is an integral part of radiology and studying radiology without images might be a futile attempt to learn it. The paucity of such publications has motivated the authors to bring out this well organized, up to date book of radiology which has all the relevant images and image-based questions along with an online pool of images, covering all the important signs and systemic diseases, which surely do not have any substitute or replacement. Review of Radiology is an attempt by authors to ensure answers for all the questions related to imaging from all the subjects of clinical domain, like surgery, medicine, obstetrics and gynecology pediatrics, orthopedics, ENT and ophthalmology. All the topics and concepts given in all the sections (General Radiology, Systemic Radiology, Radiotherapy and Nuclear Scans, Few Thumb Rules in Radiology, Image-based Questions) are not only just for the examinations but also for students \'future clinical training and day-to-day working in hospitals. Review of Radiology is surely an ideal book without which learning of medicine and preparation of entrance examination/USMLE is incomplete.''',
      link:
          'https://drive.google.com/uc?export=download&id=1v_X1d5gUbmkqvw3SbnY9xjPmQFCKX0Ky'),
  Book(
      id: 264,
      subject: 'MCQ MBBS',
      title: 'AIIMS GK with Logical Thinking',
      writer: 'Dr. MD. Usmangani Ansari',
      edition: '(2016-17)',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51gmiiRkeEL._SX318_BO1,204,203,200_.jpg',
      rating: 3.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1RuUx61HQbE9cV3nzCKJ0GBaD2UF_6w2z'),
  Book(
      id: 265,
      subject: 'Dental Materials',
      title: 'Basic dental materials',
      writer: 'john manapali',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51teOPGuzHL._SX368_BO1,204,203,200_.jpg_.jpg',
      rating: 4.7,
      description:
          '''The book retains its format of simplicity, yet at the same time latest and informative.
It helps students navigate the complex field of dental materials from the very first year of the course.
Covers the entire spectrum of materials used in dentistry, including surgical and orthodontic materials.
The contents have been revised to keep the information current and relevant.
30 chapters in the book have been organized into 7 parts for ease of reference.
Chapter outline given at the beginning of each chapter.
Includes two chapters on endodontic materials.
Metallurgy has been included in the Structure and Properties of Metals and Alloys.
Includes new chapter in the field of ‘additive manufacturing’, known as 3D printing.
Explanatory footnotes provided wherever needed.
Enriched with easy to reproduce illustrations, photographs and descriptive tables for quick learning.
Important information has been covered in boxes at relevant places in the text.
Contains appendices, further reading, and an extensive index at the end of the book.
It will prove to be indispensible to postgraduates, dental technicians and practitioners alike.''',
      link:
          'https://drive.google.com/uc?export=download&id=1UkgQhshHZC6Fp4s9os7F2wVm_SV9s3eZ'),
  Book(
      id: 266,
      subject: 'Dental Materials',
      title: 'Phillip\'s Science of Dental Materials',
      writer: 'Kenneth J. Anusavice',
      edition: '12th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41QeOqUQTCL._SX376_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''Learn the most up to date information on materials used in the dental office and laboratory today. Emphasizing practical, clinical use, as well as the physical, chemical and biological properties of materials, this leading reference helps you stay current in this very important area of dentistry. This new full color edition also features an extensive collection of new clinical photographs to better illustrate the topics and concepts discussed in each chapter.''',
      link:
          'https://drive.google.com/uc?export=download&id=1D3zgbwu0NwLT-HUbUc_b0Ts-lY07ltEp'),
  Book(
      id: 267,
      subject: 'Dental Materials',
      title: 'Delmar\'s Dental Materials Guide, Spiral bound Version',
      writer: 'Donna J. Phinney (Author), Judy H. Halstead (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/418yE3cPQbL._SY319_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1C2w67axDMR9KLQ-nbik9g3pGpNZga4Ia'),
  Book(
      id: 268,
      subject: 'Dental Materials',
      title: 'Biocompatibility of Dental Materials',
      writer: 'Irwin M. Freedberg (Editor), Thomas B. Fitzpatrick (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41qhY%2BOUWfL._SX349_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1jWVLCMt0Uy4rfmQ-xCDqMe0ddKM5bwzV'),
  Book(
      id: 269,
      subject: 'Dental Materials',
      title: 'Dental Materials at a Glance (At a Glance (Dentistry))',
      writer: 'von Fraunhofer, J. Anthony (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51YIYa4JqnL._SX385_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''Dental Materials at a Glance, 2nd edition, is the latest title in the highly popular At a Glance series, providing a concise and accessible introduction and revision aid. Following the familiar, easy-to-use at a Glance format, each topic is presented as a double-page spread with key facts accompanied by clear diagrams encapsulating essential information.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Jjt_awbluxgr9xsd4F5DcpWimHXszW8C'),
  Book(
      id: 270,
      subject: 'Dental Materials',
      title: 'Craig\'s Restorative Dental Materials',
      writer: 'Authors: Ronald Sakaguchi John Powers',
      edition: '13th',
      image:
          'https://secure-ecsd.elsevier.com/covers/80/Tango2/large/9780323081085.jpg',
      rating: 4.5,
      description:
          '''Master the use of dental materials in the clinic and dental laboratory and stay current with this ever-changing field with Craig\'s Restorative Dental Materials, 13th Edition. From fundamental concepts to advanced skills, this comprehensive text details everything you need to know to understand the scientific basis for selecting dental materials when designing and fabricating restorations. This practical, clinically relevant approach to the selection and use of dental materials challenges you to retain and apply your knowledge to realistic clinical scenarios, giving you an authoritative advantage in dental practice.''',
      link:
          'https://drive.google.com/uc?export=download&id=1wBLnRWWe_YhBCybJX8W8E587km_H_nry'),
  Book(
      id: 271,
      subject: 'Dental Materials',
      title:
          'Oxford Handbook of Integrated Dental Biosciences (Oxford Medical Handbooks)',
      writer: 'Hugh Devlin (Editor), Rebecca Craven (Editor)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41KY4kpqGDL._SX274_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Practical, comprehensive, and concise, the Oxford Handbook of Integrated Dental Biosciences has been designed to reflect problem-based teaching scenarios, with extensive diagrams and illustrations to aid clinical understanding of the main text. Summary and key point boxes have been incorporated throughout to allow quick reference and easy assimilation of the content.

Formally known as the Oxford Handbook of Applied Dental Sciences, this second edition has been completely rewritten by a brand new author team, to closely integrate the non-clinical and clinical aspects of dentistry. Featuring separate sections detailing the relevant clinical application and putting the science into context, this handbook is ideal for dental students, dental trainees studying for higher qualifications, and practitioners as a useful aide memoire.''',
      link:
          'http://93.174.95.29/main/2378000/73021b3c6fac24f3e6b45114d90d577b/%28Oxford%20Medical%20Handbooks%29%20Hugh%20Devlin%2C%20Rebecca%20Craven%20-%20Oxford%20Handbook%20of%20Integrated%20Dental%20Biosciences-Oxford%20University%20Press%20%282018%29.pdf'),
  Book(
      id: 272,
      subject: 'Dental Materials',
      title: 'Dental Materials: Foundations and Applications',
      writer: 'John M. Powers PhD (Author), John C. Wataha DMD PhD (Author)',
      edition: '11th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51ZdrmWk9ML._SX371_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''Get an in-depth understanding of the dental materials and tasks that dental professionals encounter every day with Dental Materials: Foundations and Applications, 11th Edition.  Trusted for nearly 40 years, Powers and Wataha’s text walks readers through the nature, categories, and uses of clinical and laboratory dental materials in use today. Increased coverage of foundational basics and clinical applications and an expanded art program help make complex content easier to grasp. If you’re looking to effectively stay on top of the rapidly developing field of dental materials, look no further than this proven text.

Comprehensive and cutting-edge content describes the latest materials commonly used in dental practice, including those in esthetics, ceramics, dental implants, and impressions.
Approximately 500 illustrations and photographs make it easier to understand properties and differences in both materials and specific types of products.
Review questions provide an excellent study tool with 20 to 30 self-test questions in each chapter.
Quick Review boxes summarize the material in each chapter.
Note boxes highlight key points and important terminology throughout the text.
Key terms are bolded at their initial mention in the text and defined in the glossary.
Expert authors are well recognized in the fields of dental materials, oral biomaterials, and restorative dentistry.
A logical and consistent format sets up a solid foundation before progressing into discussions of specific materials, moving from the more common and simple applications such as composites to more specialized areas such as polymers and dental implants.
Learning objectives in each chapter focus readers’ attention on essential information.
Supplemental readings in each chapter cite texts and journal articles for further research and study.
Conversion Factors on the inside back cover provides a list of common metric conversions.
NEW! Foundations and Applications subtitle emphasizes material basics and clinical applications to mirror the educational emphasis.
NEW! More clinical photos and conceptual illustrations help bring often-complex material into context and facilitate comprehension.''',
      link:
          'http://93.174.95.29/main/2225000/22049419b132090e7733d476fd430f97/John%20M.%20Powers%2C%20John%20C.%20Wataha%20-%20Dental%20Materials_%20Foundations%20and%20Applications-Mosby%20%282016%29.pdf'),
  Book(
      id: 273,
      subject: 'Dental Materials',
      title: 'Handbook of Oral Biomaterials',
      writer: 'Jukka Pekka Matinlinna (Editor)',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51hMBv5q-xL._SX327_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''The book introduces the latest advances in dental materials and biomaterials science. It contains a comprehensive introduction and covers ceramic, metallic, and polymeric oral biomaterials. The contributing authors are from all over the world and are distinguished in their disciplines. A solid primer for dental students, the book is also highly recommended for students of engineering and basic science who want to gain an insight in contemporary biomaterials science. For medical practitioners, the book offers an invaluable opportunity to learn about the latest steps in dental biomaterials.''',
      link:
          'http://93.174.95.29/main/1197000/f6fa529eced8e03cea7d5c9f5172490a/Jukka%20P%20Matinlinna%20-%20Handbook%20of%20Oral%20Biomaterials-Pan%20Stanford%20Publishing%2C%20CRC%20Press%20%282014%29.pdf'),
  Book(
      id: 274,
      subject: 'Dental Materials',
      title: 'Clinical Aspects of Dental Materials',
      writer: 'Marcia Gladwin (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51ru7jfK5PL._SX383_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''Using a proven pedagogical organization, this updated Fifth Edition of Gladwin and Bagbyâ€™s market-leading title focuses on providing students with a dental materials background that emphasizes the clinical aspects of dental materials, while also introducing concepts of materials science.
The bookâ€™s three-part structure addresses types of dental materials in the 22 chapters of Part I, includes laboratory and clinical applications (essentially a built-in lab manual) in Part II, and presents 11 case studies in Part III that serve as an overall review and help students strengthen their critical thinking skills when providing patient care.
Up-to-date content that reflects the latest advances in dental materials, clinical photos, review questions, and online videos all combine to help students develop the understanding of dental materials they need for successful dental hygiene practice.''',
      link:
          'http://93.174.95.29/main/2230000/ad072e04b48dd591c01bcbd4c6b42b1c/Marcia%20Gladwin%2C%20Michael%20Bagby%20-%20Clinical%20Aspects%20of%20Dental%20Materials_%20Theory%2C%20Practice%2C%20and%20Cases-LWW%20%282017%29.epub'),
  Book(
      id: 275,
      subject: 'Dental Materials',
      title: 'BASIC GUIDE TO DENTAL INSTRUMENTS',
      writer: 'Carmen Scheller-Sheridan (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51qcoxKSYxL._SX326_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Basic Guide to Dental Instruments provides a working inventory of dental instrumentation in common use in dental surgeries. A clear photograph of each instrument is included, and described according to name, usage, any relevant features and varieties. Each section is dedicated to a specific discipline or division of dentistry. Complete set-ups have been included at the end of most sections for various procedures. The coverage reflects instrumentation and accessory items used in general dental practice, routine hospital dental procedures and selected specialist settings.
The author adopts a flexible approach which recognises that some instruments are multi-functional, and their names and usage can vary across dental surgeries. This approach, coupled with the range of instruments covered, makes the book an ideal \'portable\' resource across general practice, hospital and a range of specialist settings. The book also highlights instruments which can be easily confused. In addition to detailing the classic sets of dental instruments, the importance of instrument care and sterilisation regimes is acknowledged.

This second edition contains an expanded chapter on instruments used in conjunction with dental implants, and illustrations have been updated throughout.

FEATURES

Best-selling title
Brand new chapter on instruments used in dental implantology
Expanded chapter on dental burs
Illustrations revised throughout''',
      link:
          'http://93.174.95.29/main/1005000/8dc191f2a314e04348a81301b339aa55/Carmen%20Scheller%E2%80%90Sheridan%28auth.%29%20-%20Basic%20Guide%20to%20Dental%20Instruments%2C%20Second%20Edition-Wiley-Blackwell%20%282011%29.pdf'),
  Book(
      id: 276,
      subject: 'Dental Materials',
      title: 'Nanobiomaterials in Dentistry : Applications of Nanobiomaterials',
      writer: 'Alexandru Grumezescu (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51GNfVCghCL._SX405_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Nanobiomaterials in Dentistry: Applications of Nanobiomaterials discusses synthesis methods and novel technologies involving nanostructured bio-active materials with applications in dentistry. This book provides current research results for those working in an applied setting. The advantage of having all this information in one coherent text will be the focused nature of the chapters and the ease of which this information can be accessed.

This collection of titles brings together many of the novel applications these materials have in biology and discusses the advantages and disadvantages of each application and the perspectives of the technologies based on these findings. At the moment there is no other comparable book series covering all the subjects approached in this set of titles.

Offers an updated and highly structured reference material for students, researchers, and practitioners working in biomedical, biotechnological, and engineering fields
Serves as a valuable resource of recent scientific progress, along with most known applications of nanomaterials in the biomedical field
Features novel opportunities and ideas for developing or improving technologies in nanomedicine and dentistry''',
      link:
          'http://93.174.95.29/main/1578000/f2f129375596faed50a6e2a7b38728fb/%28Applications%20of%20nanobiomaterials%2011%29%20Alexandru%20Grumezescu%20-%20Nanobiomaterials%20in%20Dentistry.%20Applications%20of%20Nanobiomaterials%20Volume%2011-William%20Andrew%20%282016%29.pdf'),
  Book(
      id: 277,
      subject: 'Dental Materials',
      title: 'Materials, Chemicals and Methods for Dental Applications',
      writer: 'Johannes Karl Fink  (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51NhRKLOMKL._SX331_BO1,204,203,200_.jpg',
      rating: 3.5,
      description:
          '''This book focuses on the materials used for dental applications looking at the fundamental issues and the developments that have taken place the past decade. While it provides a broad overview of dental materials, the chemicals that are used for the preparation and fabrication of dental materials are explained as well. Also, the desired properties of these materials are discussed and the relevance of the chemical, physical, and mechanical properties is elucidated. Methods for the characterization and classification, as well as clinical studies are reviewed here. In particular, materials for dental crowns, implants, toothpaste compositions, mouth rinses, as well as materials for toothbrushes and dental floss are discussed. For example, in toothpaste compositions, several classes of materials an chemcials are incorporated, such as abrasives, detergents, humectants, thickeners, sweeteners, coloring agents, bad breath reduction agents, flavoring agents, tartar control agents, and others. These chemicals, together with their structures, are detailed in the text.''',
      link:
          'http://93.174.95.29/main/2226000/e9ae37cd2fa4f7ea0ab9a5226a1def63/Johannes%20Karl%20Fink%20-%20Materials%2C%20Chemicals%20and%20Methods%20for%20Dental%20Applications-Wiley-Scrivener%20%282018%29.pdf'),
  Book(
      id: 278,
      subject: 'Dental Materials',
      title: 'Dental Materials: Properties and Manipulation',
      writer: 'John M. Powers  (Author), John C. Wataha (Author)',
      edition: '10th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51sDn9yuT1L._SX384_BO1,204,203,200_.jpg',
      rating: 3.5,
      description:
          '''Focusing on the dental materials most commonly used, Dental Materials: Properties and Manipulation, 10th Edition covers the tasks that dental assistants and dental hygienists typically perform. It shows the most current materials, how to mix and apply them in a clinical setting, and how to educate patients about them. Now in full color, this edition adds more photographs of materials actually being mixed, used, and applied, and includes detailed coverage of ceramics, metals, and implant and impression materials. Written by well-known experts on restorative dentistry and materials, John Powers and John Wataha, Dental Materials is a trusted text that keeps you on top of the rapidly developing field of dental materials.

Comprehensive, focused coverage includes all the materials and tasks relevant to day-to-day practice of dental assistants and dental hygienists.
Cutting-edge content describes the latest materials commonly used in dental practice, including those in esthetics, ceramics, dental implants, and impressions.
More than 400 illustrations and photographs make it easier to understand properties and recognize differences in materials in general and specific types of products.
Discussions of materials begin with a study of their properties and uses before moving into specific manipulations and applications in dentistry.
Note boxes highlight key points and important terminology throughout the text.
Summary tables and boxes summarize key concepts and procedures.
Quick Review boxes summarize the material in each chapter.
A logical format sets up a solid foundation before progressing into discussions of specific materials, moving from the more common and simple applications such as composites to more specialized areas such as polymers and dental implants.
Review questions provide an excellent study tool with 20 to 30 self-test questions in each chapter.
Key terms are listed at the outset of each chapter, bolded at their initial mention in the text, and defined in the glossary.
Learning objectives in each chapter focus your attention on essential information.
Supplemental readings in each chapter cite texts and journal articles for further research and study.
Conversion Factors on the inside back cover provides a list of common metric conversions.
Expert authors are well recognized in the fields of dental materials, oral biomaterials, and restorative dentistry.
New and updated discussions address advances in areas such as esthetics, ceramics, and materials for dental impressions and dental implants.
Full-color illustrations improve clarity and realism, including for example, color photos of esthetics and bleaching showing the differences in shades of color.
More than 100 new illustrations and photographs include images showing the materials being used and applied.''',
      link:
          'http://93.174.95.29/main/2225000/5d930fc96293f0192dc1d9a6f26b2b44/John%20M.%20Powers%2C%20John%20C.%20Wataha%20-%20Dental%20Materials_%20Properties%20and%20Manipulation-Mosby%20%282012%29.pdf'),
  Book(
      id: 279,
      subject: 'Dental Materials',
      title:
          'Non-Metallic Biomaterials for Tooth Repair and Replacement (Woodhead Publishing Series in Biomaterials)',
      writer: 'P Vallittu (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41pFZBjrHKL._SX313_BO1,204,203,200_.jpg',
      rating: 2.9,
      description:
          '''As the demand for healthy, attractive teeth increases, the methods and materials employed in restorative dentistry have become progressively more advanced. Non-metallic biomaterials for tooth repair and replacement focuses on the use of biomaterials for a range of applications in tooth repair and, in particular, dental restoration.

Part one reviews the structure, modification and repair of dental tissues. The properties of enamel and dentin and their role in adhesive dental restoration are discussed, along with biomineralization and biomimicry of tooth enamel, and enamel matrix proteins (EMPs) for periodontal regeneration. Part two goes on to discuss the processing, bonding and wear properties of dental ceramics, glasses and sol-gel derived bioactive glass ceramics for tooth repair and replacement. Dental composites for tooth repair and replacement are then the focus of part three, including composite adhesive and antibacterial restorative materials for dental applications. The effects of particulate filler systems on the properties and performance of dental polymer composites are considered, along with composite based oral implants, fibre reinforced composites (FRCs) as dental materials and luting cements for dental applications.

With its distinguished editor and international team of expert contributors, Non-metallic biomaterials for tooth repair and replacement provides a clear overview for all those involved in the development and application of these materials, including academic researchers, materials scientists and dental clinicians.
Discusses the properties of enamel and dentin and their role in adhesive dental restoration
Chapters also examine the wear properties of dental ceramics, glasses and bioactive glass ceramics for tooth repair and replacement
Dental composites and antibacterial restorative mateirals are also considered''',
      link:
          'http://93.174.95.29/main/880000/1e99aa5e3bdb7f5a8ab9bf7e166a5cef/%28Woodhead%20Publishing%20Series%20in%20Biomaterials%29%20Pekka%20Vallitu%20-%20Non-metallic%20biomaterials%20for%20tooth%20repair%20and%20replacement-Woodhead%20Publishing%20%282013%29.pdf'),
  Book(
      id: 280,
      subject: 'Dental Materials',
      title: 'Advanced Ceramics for Dentistry',
      writer: 'James Shen (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51a6UOG8WqL._SX336_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''The growth of implant and fixed prosthodontics practices in dentistry has created a rapidly increasing demand for advanced ceramics and ceramic processes. Innovations in ceramics and ceramic processes are vital to ensure reliable and affordable dental-restoration solutions with aesthetically pleasing outcomes.

The work aims to engage the bioceramics and engineering communities to meet the challenges of modern dental restoration using advanced ceramics. Incorporating fundamental science, advanced engineering concepts, and clinical outcomes, the work is suitable for bioceramicists, ceramics manufacturers, dental clinicians and biologists.

State-of-the-art-coverage encompasses bioresorbable ceramics for bone regeneration and bioactivating surfaces of inert, high-strength ceramics for implantation, keeping research knowledge appropriately updated
Discusses transition from the baseline stable and physically stiff ceramics research into engineering of highly coherent laminate composites for prosthetic crowns and bridges
Showcases current feasible techniques for producing, in cost-effective and materials-saving ways, long-lasting individualized ceramic components with biocompatibility, complexity and high precision''',
      link:
          'http://93.174.95.29/main/1038000/1606d68814005d07d354b9944dceec59/James%20Shen%20-%20Advanced%20Ceramics%20for%20Dentistry-Butterworth-Heinemann%20%282013%29.pdf'),
  Book(
      id: 281,
      subject: 'Dental Materials',
      title:
          'The Chemistry of Medical and Dental Materials (RSC Materials Monographs)',
      writer: 'John W Nicholson  (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41Jtvw7sndL._SX339_BO1,204,203,200_.jpg',
      rating: 3.5,
      description:
          '''Implants into the human body, such as hip joints, heart valves and dental crowns, have been increasingly used over the last 40 years or so, and many patients have benefited from their use. But how much is known about the metals, ceramics and polymers that are used in these repairs? This book provides a state-of-the-art account of the chemistry of the synthetic materials used in medicine and dentistry. It looks at the properties and interactions of these materials within the body at a molecular level, and includes discussion of bioengineering and cell biology. In addition, there is an account of the surgical procedures used, as well as extensive coverage of the possible biological reactions to the presence of foreign materials in the body. A brief look at the emerging field of tissue engineering completes the text. Fully referenced, with detailed reviews of the current literature, The Chemistry of Medical and Dental Materials will be an essential starting-point for all those in academia and industry who are involved in the development of new and improved repair materials.''',
      link:
          'http://93.174.95.29/main/116000/f0e3d26a5ec0c12285671cb8ecb62133/%28Rsc%20Materials%20Monographs%29%20J.W.%20Nicholson%20-%20The%20Chemistry%20of%20Medical%20and%20Dental%20Materials-Royal%20Society%20of%20Chemistry%20%282002%29.pdf'),
  Book(
      id: 282,
      subject: 'oral anatomy',
      title: 'Orban\'s Oral Histology and Embryology',
      writer: 'G. S. Kumar',
      edition: '14th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51mCQ9Hmc%2BL._SX387_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'http://93.174.95.29/main/2225000/f8fbef18a33a0e72839757c3bb96c358/%28Package%20deal%29%20G.%20S.%20Kumar%20-%20Orban%E2%80%99s%20Oral%20Histology%20and%20Embryology-Elsevier%20India%20%282018%29.pdf'),
  Book(
      id: 283,
      subject: 'oral anatomy',
      title: 'Wheeler\'s Dental Anatomy, Physiology and Occlusion',
      writer: 'Stanley J. Nelson DDS MS',
      edition: '10th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51B8PKZ6VML._SX393_BO1,204,203,200_.jpghttps://images-na.ssl-images-amazon.com/images/I/51B8PKZ6VML._SX393_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''Applying dental anatomy to the practice of dentistry, Wheeler’s Dental Anatomy, Physiology, and Occlusion, 10th Edition provides illustrated coverage of dentitions, pulp formation, the sequence of eruptions, and clinical considerations. The market leader, this text is used as a reference in creating examination questions for the dental anatomy and occlusion section of the NBDE Part I. This edition expands its focus on clinical applications and includes dozens of online 360-degree and 3-D tooth animations. Written by expert educator and lecturer Dr. Stanley Nelson, Wheeler’s Dental Anatomy provides a solid foundation in this core subject for the practice of dentistry.

Over 900 full-color images include detailed, well-labeled anatomical illustrations as well as clinical photographs
Practical appendices include Review of Tooth Morphology with a concise review of tooth development from in utero to adolescence to adulthood, and Tooth Traits of the Permanent Dentition with tables for each tooth providing detailed information such as tooth notation, dimensions, position of proximal contacts, heights, and curvatures. 
360-degree virtual reality animations on the Evolve companion website demonstrate 26 tooth views from multiple directions, while 27 3-D animations demonstrate dental structure and mandibular movement, helping you refine your skills in tooth identification and examination. 
64 detachable flash cards show tooth traits and many illustrations from the book, making it easy to prepare for tests as well as for the NBDE and NBDHE.
32 labeling exercises on Evolve challenge you to identify tooth structures and facial anatomy with drag-and-drop labels.
NEW Clinical Applications of Dental Anatomy, Physiology and Occlusion chapter includes practical applications and case studies, including instructions on root planing and scaling, extraction techniques and forces, relationship of fillings to pulp form and enamel form, and occlusal adjustment of premature occlusal contacts and arch form in relationship to bite splint designs, all preparing you for the NBDE’s new focus on clinical applications. 
NEW photos, illustrations, and research keep you up to date with the latest dental information.
Three NEW animations on the Evolve companion website demonstrate occlusal adjustments.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Aaxb3Xa3z3zuFtbpLq4PVIypY_rfR6I6'),
  Book(
      id: 284,
      subject: 'oral anatomy',
      title: 'Oral Anatomy, Histology and Embryology',
      writer:
          'Barry K.B Berkovitz BDS MSc PhD FDS (Eng) (Author), G. R. Holland BSc BDS PhD CERT ENDO (Author), Bernard J. Moxham BSc BDS PhD FHEA FRSB Hon FAS FSAE (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51BAL%2BV5vbL._SX405_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''The new edition of this now classic book continues to provide dental students with all of the information required to ensure a complete understanding of oral anatomy, histology and embryology as they relate to dental practice. Authored by experts of international renown, the high-quality images and clearly written text found within this volume – features which strongly characterised the high success of previous editions - make study of these challenging topics as easy as possible.
Presents a unique, integrative approach to oral dental science by covering aspects of gross anatomy, tooth morphology, radiology, oral histology and embryology in one volume
Features approximately 1100 high-quality colour images, one quarter of which are previously unpublished
Contains useful ‘clinical application’ boxes to clearly show relevance of subject area to routine dental practice
Completely revised section on tooth morphology with improved specimens and digital photography
Contains a new chapter on the effects of ageing to highlight the important changes taking place in the oro-dental tissues in an increasingly ageing population
New design aids learning by the inclusion of clearer diagrams and high quality, larger format digital images''',
      link:
          'http://93.174.95.29/main/2232000/d2c75d67a5882c253f0a82f8d88c0917/Barry%20K.%20B.%20Berkovitz%2C%20G.%20R.%20Holland%2C%20Bernard%20J.%20Moxham%20-%20Oral%20Anatomy%2C%20Histology%20and%20Embryology-Mosby%20%282009%29.pdf'),
  Book(
      id: 285,
      subject: 'oral anatomy',
      title:
          'Basic Guide to Anatomy and Physiology for Dental Care Professionals',
      writer: 'Carole Hollins  (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/412Sw4W4thL._SX331_BO1,204,203,200_.jpg',
      rating: 3.2,
      description:
          '''The Basic Guide to Anatomy and Physiology for Dental Care Professionals introduces the fundamentals of human anatomy and physiology to the student Dental Care Professional.
Written in a clear, accessible style, it provides dental nurses, hygienists, therapists and clinical dental technicians with essential grounding in the head and neck area, as well as all the body systems that have implications for the DCP when things go wrong.

Beginning with a definition of anatomy and physiology, and with all the basics of cell, tissue and organ biology, this Basic Guide covers:

the cardiovascular, respiratory and digestive systems, all of which are central to the DCP curriculum
core areas such as skull and oral anatomy, periodontal tissues, blood and nerve supply to the oral cavity, muscles of mastication, and major salivary glands
areas such as jaw and tooth development, and the histology or oral and dental tissue
Each area is covered separately and in depth, giving the reader an understanding of their structure and function in health as well as illnesses relevant to medical emergencies and dental-related disorders (such as acid reflux which causes tooth erosion).''',
      link:
          'http://93.174.95.29/main/1101000/0ffcc1db061d8816cabd4d99bc7e8da6/%28Basic%20Guide%20Dentistry%20Series%29%20Carole%20Hollins%20-%20Basic%20Guide%20to%20Anatomy%20and%20Physiology%20for%20Dental%20Care%20Professionals-Wiley%20%282012%29.pdf'),
  Book(
      id: 286,
      subject: 'oral anatomy',
      title: 'Dental Embryology, Histology and Anatomy',
      writer: 'Margaret J. Fehrenbach RDH MS (Author), Tracy Popowics (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41n7vsEhu1L._SX389_BO1,204,203,200_.jpg',
      rating: 3.5,
      description:
          '''Featuring a full-color review of dental structures, Illustrated Dental Embryology, Histology, and Anatomy, 4th Edition, provides a complete look at the development, cellular makeup, and morphology of the teeth and associated structures. A clear, reader-friendly writing style makes it easy to understand both basic science and clinical applications, putting the material into the context of everyday dental practice. New to this edition are updates on caries risk, safe levels of fluoride use, and prevention of periodontal disease. Expert authors Margaret Fehrenbach and Tracy Popowics provide an essential background in oral biology for student dental professionals, including excellent preparation for board exams.
Comprehensive coverage includes all the content needed for an introduction to the developmental, histological, and anatomic foundations of oral health.
Hundreds of full-color anatomical illustrations and clinical and microscopic photographs accompany text descriptions of anatomy and biology.
An approachable writing style covers the latest evidence-based information and makes it easy to grasp and learn to apply the material.
A logical organization separates the book into four units for easier understanding: (1) an introduction to dental structures, (2) dental embryology, (3) dental histology, and (4) dental anatomy.
Key terms open each chapter, accompanied by phonetic pronunciations, and are highlighted within the text, and a glossary provides a quick and handy review and research tool.
Clinical Considerations boxes relate abstract-seeming biologic concepts to everyday clinical practice.
Learning outcomes at the beginning of each chapter clearly identify the information you are expected to absorb.
Summary tables and boxes provide quick, easy-to-read summaries of concepts and procedures and serve as useful review and study tools.
Student resources on the Evolve companion website enhance learning with practice quizzes, samplecase studies, review questions, and interactive exercises.
A bibliography lists resource citations for further research and study.
Expert primary author Margaret Fehrenbach is one of the most trusted names in dental education, and writes extensively, lectures widely, and consults for many of the major dental manufacturers and supply companies.
NEW! Updated coverage includes the newest evidence-based information on orofacial embryology, especially enamel formation; orofacial histology including fibroblasts, microplicae, keratin, collagen proteins, aging, repair, 3-D tissue engineering, mucoperiosteum, dental pulp stem cells, and platelet-rich plasma; root anatomy; and the latest guidelines on dental biofilm, fluoride use, smile design, periodontal procedures, endoscopy, saliva testing, enamel remineralization, periimplant disease, myofunctional therapy, and orthodontic therapy intervention.
NEW color illustrations, photomicrographs, and diagrams add detail and help to build comprehension.
NEW secondary author Tracy Popowics, PhD, provides research and expertise related to advanced dental content.
A student workbook offers a wealth of interactive exercises, including labeling/structure identification to master anatomy, word-search and crosswordpuzzles for vocabulary practice, detailed guidelines for tooth drawing, and illustrated case studies with follow-up questions; in the back of the book, 32 removable flashcards provide practice on identifying permanent teeth and their features and characteristics. Sold separately.''',
      link:
          'http://93.174.95.29/main/1547000/61d6f941478ab9fc3dbaaf803da989fd/Margaret%20J.%20Fehrenbach%20RDH%20%20MS%2C%20Tracy%20Popowics%20-%20Illustrated%20Dental%20Embryology%2C%20Histology%2C%20and%20Anatomy%2C%204e-Saunders%20%282015%29.pdf'),
  Book(
      id: 287,
      subject: 'oral anatomy',
      title: 'Woelfels Dental Anatomy',
      writer: 'Rickne C. Scheid (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51JYWW-CUTL._SX382_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''The bookâ€™s detailed coverage of dental anatomy and terminology prepares students for success on national board exams, while up-to-date information on the application of tooth morphology to dental practice prepares them for success in their future careers.
Updated throughout with the latest scientific and technological advances, the Ninth Edition features expanded content, new tooth identification labeling exercises, additional board-style learning exercises, and a substantially updated full color art and design program.''',
      link:
          'http://93.174.95.29/main/2225000/648cb2169b0d79b39e9789f1196d2117/Rickne%20C.%20Scheid%2C%20Gabriela%20Weiss%20-%20Woelfels%20Dental%20Anatomy-LWW%20%282016%29.pdf'),
  Book(
      id: 288,
      subject: 'oral anatomy',
      title: 'MCQs for Netter’s Head and Neck Anatomy for Dentistry',
      writer: 'Author',
      edition: '2nd',
      image:
          'https://libgen.is/covers/2329000/29f9c89d73f5f7e07b11154706dfba30-d.jpg',
      rating: 3.9,
      description: '''''',
      link:
          'http://93.174.95.29/main/2329000/29f9c89d73f5f7e07b11154706dfba30/Elsevier%20Ltd%20-%20MCQs%20for%20Netter%E2%80%99s%20Head%20and%20Neck%20Anatomy%20for%20Dentistry%20%282015%29.pdf'),
  Book(
      id: 289,
      subject: 'oral anatomy',
      title: 'Primary Tooth Development in Infancy : A Text and Atlas',
      writer:
          'P. Sema Aka (Author), Murat Yagan (Author), Nergis Canturk (Author), Rukiye Dagalp (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Oj%2B77JSXL._SX365_BO1,204,203,200_.jpg',
      rating: 3.0,
      description:
          '''Primary Tooth Development in Infancy: A Text and Atlas describes the initial phase of human dentition. It includes more than 1,500 photographs of fetal and infant teeth up to the age of one year. The book presents each step in the developmental phases in photographs accompanied by concise explanatory text. The teeth are photographed from six different aspects: labial, lingual, mesial, distal, incisal, and from the root direction and includes CT images in some cases.

Topics covered include morphology and development of primary dentition, discrimination criteria for human dentitions, forensic importance of direct and indirect measuring techniques, dental identification and age estimation from teeth, achieving dental evidence from oral autopsy, and age estimation formulae. The book also discusses the neonatal line concept of intrauterine life accompanied by corresponding scanning electron microscope photographs.

A supplementary software program for age estimation from dental measurements can also be used in conjunction with the material in this text. Meticulously prepared by a team of experts, this atlas is a valuable tool for odontologists, pediatricians, pedodontists, forensic scientists, and dental anthropologists.''',
      link:
          'http://93.174.95.29/main/1378000/26b5108cec1cde2f239bbb1e64d28d09/Aka%2C%20P.%20Sema_%20Canturk%2C%20Nergis_%20Dagalp%2C%20Rukiye_%20Yagan%2C%20Murat%20-%20Primary%20Tooth%20Development%20in%20Infancy%20_%20A%20Text%20and%20Atlas-CRC%20Press%20%282015%29.pdf'),
  Book(
      id: 290,
      subject: 'oral anatomy',
      title: 'Textbook of Dental Anatomy, Physiology and Occlusion',
      writer: 'Rashmi G. S. Phulari (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51ptw7SPrIL._SX365_BO1,204,203,200_.jpg',
      rating: 3.0,
      description:
          '''This textbook is a comprehensive guide to dental anatomy, physiology and occlusion (alignment), for postgraduate dental students.

Beginning with an introduction to anatomy and tooth development, the following chapters provide in depth discussion on deciduous and permanent dentition, morphology of teeth, and occlusion. The final section is dedicated to tooth carving, providing step by step methodology.

Each chapter includes multiple choice questions and answers to help students prepare for exams, and features numerous high quality photographs and diagrams with descriptions.

Two interactive DVDs are included, demonstrating tooth carving procedures for different teeth, and providing more multiple choice questions for self assessment.


Key points

Comprehensive guide to dental anatomy, physiology and occlusion for postgraduate students
Complete section dedicated to tooth carving
Multiple choice questions in each chapter
Includes DVDs demonstrating tooth carving procedures''',
      link:
          'http://93.174.95.29/main/1447000/8974e1d0dfeace97f4fd49248df863a9/Rashmi%20G%20S%20%28Phulari%29%20-%20Textbook%20of%20Dental%20Anatomy%2C%20Physiology%20and%20Occlusion-Jaypee%20Brothers%20Medical%20Publishers%20%282014%29.pdf'),
  Book(
      id: 291,
      subject: 'oral anatomy',
      title: 'Fundamentals of Oral Histology and Physiology',
      writer: 'Arthur R. Hand (Author), Marion E. Frank  (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51XLdNLuHLL._SX385_BO1,204,203,200_.jpg',
      rating: 3.2,
      description:
          '''Fundamentals of Oral Histology and Physiology is a landmark new text streamlining the essentials of histology and physiology into one clinically accessible textbook. Written for predoctoral dental students, the book brings together structure, function, and clinical correlations for maximum retention and ease of use.

Assuming a background in basic biologic sciences, this text focuses on the histology and physiology that students need to know to practice dentistry and to understand and evaluate the current literature, without repeating basic information learned in other courses. Fundamentals of Oral Histology and Physiology concentrates on Oral Structures and Features, including Development, Teeth, Tooth and Jaw Support, Mucosal Structure and Function, and Effectors.''',
      link:
          'http://93.174.95.29/main/1298000/5e09c469a4a2b91115295e0031d9c719/Arthur%20R.%20Hand%2C%20Marion%20E.%20Frank%20-%20Fundamentals%20of%20Oral%20Histology%20and%20Physiology-Wiley-Blackwell%20%282015%29.pdf'),
  Book(
      id: 292,
      subject: 'oral anatomy',
      title: 'Ten Cate\'s Oral Histology: Development, Structure, and Function',
      writer: 'Antonio Nanci PhD (Editor)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51IbizWuajL._SX388_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Gain a deeper understanding of oral health with the definitive text in oral histology. Written by Dr. Antonio Nanci, a world-renowned leader in cell biology, the new ninth edition of Ten Cate’s Oral Histology covers all the latest research and trends in oral histology, embryology, physiology, oral biology, and postnatal growth and development that is essential to success in oral health! Considered to be the standard in the field, this renowned text uses straightforward explanations and detailed, full-color micrographs, images, and illustrations to help you better understand even the most complex topics.

Detailed histological and structural images help you differentiate the structures.
Medical approach to histology helps you understand underlying biological events, and oral tissue repair and regeneration.
Full-color format helps bring oral histology to life.
Learning resources on the Evolve website include multiple-choice review questions with instant feedback, and interactive drag-and-drop exercises.
NEW! Full-color micrographs, images, and 3D art enhance your understanding of key oral histology concepts.
NEW! Commentary boxes highlight new and innovative research topics from leaders in the field.
NEW! Updated content ― including additional content on the nervous system in chapter four ― has been added to keep you up to date with the latest information in the field.''',
      link:
          'http://93.174.95.29/main/2228000/5eeb03833bf7ab9ef7d1964213c9fcfd/Antonio%20Nanci%20-%20Ten%20Cate%E2%80%99s%20Oral%20Histology_%20Development%2C%20Structure%2C%20and%20Function-Elsevier%20%282017%29.mobi'),
  Book(
      id: 293,
      subject: 'Prosthodontics',
      title: 'Textbook of Prosthodontics',
      writer: 'V Rangarajan (Author), T V Padmanabhan (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51DWls5mYkL._SX382_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''Textbook of Prosthodontics encompasses all the different subspecialities of prosthodontics like Complete Dentures (CD), Removable Partial Dentures (RPD), Fixed Partial Dentures (FPD), Oral Implantology (OI) and Maxillofacial Prosthetics (MFP) with an aim to demystify the subject. The book provides a strong basic foundation along with contemporary clinical and laboratory applications. The book is written in an easy -to-comprehend-and-remember style, the clinical and laboratory aspects are depicted with colour photographs, radiographs, line arts, tables, boxes and flowcharts to make text self-explanatory

Covers DCI prescribed syllabus for UGs
Contains numerous tables, boxes, flowcharts and more than 3000 high quality colour photos and line diagrams to supplement the text
Contains dedicated chapters on Porcelain Laminate Veneers, Attachment Retained Dentures, Overdentures, and Smile Design
Provides section wise Suggested Reading and chapter wise Sample Questions in Appendices section
Companion website (www.manthan.info/) provides latest Glossary of Prosthodontic Terms for additional reading''',
      link:
          'https://drive.google.com/uc?export=download&id=1j59sCtuUOEmRRT6I52EnedhGhKydtbpv'),
  Book(
      id: 294,
      subject: 'Prosthodontics',
      title: 'Textbook of Prosthodontics Nallaswamy',
      writer: 'Deepak Nallaswamy',
      edition: '2nd',
      image:
          'https://booksbeka.com/image/cache/catalog/002017%20update/FOR%20CATEGORIES/B9789351524441-500x500.jpg',
      rating: 4.3,
      description:
          '''Ever for the reason that i used to be a first year dental undergraduate student, desired to jot down a ebook like gray’s Anatomy this is considered equal to the Bible in Anatomy. As soon as entered internship I labored difficult to develop the elegance notes in prosthodontics. This ended in my first edition Of the Textbook of Prosthodontics.

I had labored very difficult on this undertaking and i’m very proud to have written this incredible e book. desired the next edition to be a well cited, evidence-based totally cheesecake of rich prosthodontics literature. Obviously this type of tall ambition have become a enormous project to conquer. It required fantastic interest to element and determination which in-turn extended the cut-off date for extra than a long time!

I firmly accept as true with such accomplishments Will continue to be as fossils of my legacy in teaching. Interposed inside this fashionable matrix. you will find treasured gem stones of information that are packed in for advanced readers.''',
      link:
          'https://drive.google.com/uc?export=download&id=1WUG2Q4cV_HfPs9F8Ta2mOmi9Y-hR_1vU'),
  Book(
      id: 295,
      subject: 'conservative dentistry',
      title: 'Textbook Of Operative Dentistry',
      writer: 'Garg Nisha (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51zVFFp9VlL._SX359_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''Textbook of Operative Dentistry is the latest edition of this richly illustrated resource, covering diagnosis, treatment and prognosis of dental problems which do not require full coverage restoration. This new edition has been completely revised and updated, with 722 full colour images and illustrations and substantial revisions in every chapter, incorporating the latest developments in the field and current research findings. Divided into 24 chapters, this book emphasises a practical approach and clear advice on the selection and use of modern dental materials, and describes how teeth are prepared for indirect restorations such as crowns, bridges and inlays. The initial chapters cover dental terminology, physiology, instruments, patient evaluation, diagnosis and treatment, infection control and pain management, amongst many other topics. Further chapters cover a broad range of operative procedures. The book also emphasises the importance of aesthetics in modern dentistry. Textbook of Operative Dentistry combines proven methods with the latest scientific developments in preventive and restorative dentistry, including nanodentistry, bringing this essential edition fully up to date. Key Points Latest edition of illustrated guide to dental restoration Previous edition published 2012 (9789350259399) Combines proven methods with the latest scientific developments in the field 722 full colour images and illustrations''',
      link:
          'https://drive.google.com/uc?export=download&id=1GMhVApeoW4K8WKdwi13kxEzM17tvpuVL'),
  Book(
      id: 296,
      subject: 'conservative dentistry',
      title:
          'Sturdevant\'s Art & Science of Operative Dentistry A South Asian Edition',
      writer: 'Gopi Krishna Roberson (Author)',
      edition: '7th',
      image: 'https://images-eu.ssl-images-amazon.com/images/I/41RlJh9ZdcL.jpg',
      rating: 4.3,
      description: '''This Indispensible text…

From 1968, this classic textbook has been the foundational text on operative dentistry
Amalgamates both theoretical and practical knowledge, and is supported by extensive clinical and laboratory research
Presents an illustrated step-by-step approach to conservative, restorative and preventive dentistry
Provides a thorough understanding of caries and an authoritative approach to its treatment and prevention
New to this South Asia Edition…

Reader friendly: Adapted keeping in mind the curriculum of the final year undergraduate student with exam and clinical oriented Clinical Notes boxes. The text is streamlined for improved readability
Full Color Design: Incorporates more than 497 illustrations including color photos and around 100 tables and boxes to better show techniques and detail
Added Chapters: Three new chapters on Restoring Contacts and Contours, Noncarious Lesions and their Management and Dentin Hypersensitivity have been included in this edition
Companion website: The website features three online chapters for additional study
This Indispensible text…

From 1968, this classic textbook has been the foundational text on operative dentistry
Amalgamates both theoretical and practical knowledge, and is supported by extensive clinical and laboratory research
Presents an illustrated step-by-step approach to conservative, restorative and preventive dentistry
Provides a thorough understanding of caries and an authoritative approach to its treatment and prevention
New to this South Asia Edition…

Reader friendly: Adapted keeping in mind the curriculum of the final year undergraduate student with exam and clinical oriented Clinical Notes boxes. The text is streamlined for improved readability
Full Color Design: Incorporates more than 497 illustrations including color photos and around 100 tables and boxes to better show techniques and detail
Added Chapters: Three new chapters on Restoring Contacts and Contours, Noncarious Lesions and their Management and Dentin Hypersensitivity have been included in this edition
Companion website: The website features three online chapters for additional study''',
      link:
          'https://drive.google.com/uc?export=download&id=1KrpEsdXwTn9K3oZYYuRC6cAVZS8lSl0X'),
  Book(
      id: 297,
      subject: 'conservative dentistry',
      title: 'Management of Deep Carious Lesions',
      writer: 'Falk Schwendicke (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/4105tVQjlpL._SX320_BO1,204,203,200_.jpg',
      rating: 3.2,
      description:
          '''This book describes the challenges that deep carious lesions pose for dental practitioners, including the risk of endodontic complications and the difficulty of restorative treatment, and identifies options for overcoming these challenges on the basis of the best available evidence. The opening chapter sets the scene by discussing pathophysiology, histopathology, clinical symptomatology, and treatment thresholds. The various treatment options are then systematically presented and reviewed, covering non-selective, stepwise, and selective carious tissue removal and restoration, sealing of lesions using resin sealants or crowns, and non-restorative management approaches. In each case the current evidence with respect to the treatment is carefully evaluated. Advantages and disadvantages are explained and recommendations made on when to use the treatment in question. Illustrative clinical cases and treatment pathways for clinicians are included. This book will be of value for all practitioners who treat dental caries and carious lesions, whether in the permanent or the primary dentition. It will also be of interest to under- and postgraduate students in cariology and restorative, operative, preventive, and pediatric dentistry.''',
      link:
          'http://93.174.95.29/main/2179000/8aacf8274d8bbb27b0e6759156c19331/Falk%20Schwendicke%20%28eds.%29%20-%20%20Management%20of%20Deep%20Carious%20Lesions-Springer%20International%20Publishing%20%282018%29.pdf'),
  Book(
      id: 298,
      subject: 'conservative dentistry',
      title: 'Sturdevant’s Art and Science of Operative Dentistry',
      writer: 'Andre V. Ritter DDS MS (Author)',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41WiUppqKDL._SX389_BO1,204,203,200_.jpg',
      rating: 3.2,
      description:
          '''Get a better picture of operative dentistry from the most complete text on the market. Using a heavily illustrated, step-by-step approach, Sturdevant’s Art and Science of Operative Dentistry, 7th Edition helps you master the fundamentals and procedures of restorative and preventive dentistry and learn to make informed decisions to solve patient needs. Drawing from both theory and practice and supported by extensive clinical and laboratory research, this new full-color edition features four new chapters and updated information in the areas of color and shade matching, light curing, periodontology, digital dentistry and more. It’s the practicing dentist’s complete guide to all aspects of operative dentistry.

Four new chapters cover the areas of color and shade matching, light curing, periodontology, and digital dentistry.
Expert Consult website with five supplemental chapters and procedure videos.
Evidence-based approach is supported by extensive clinical and laboratory research.
Comprehensive coverage provides a thorough understanding of caries and an authoritative approach to its treatment and prevention.
Illustrated step-by-step approach offers a better picture of conservative restorative and preventive dentistry.
Full color design clearly demonstrates techniques and details.
NEW! Four new chapters cover the areas of color and shade matching, light curing, periodontology, and digital dentistry.
NEW! Expert Consult website includes five additional online-only chapters, procedure videos, and references linked to PubMed.
NEW! Updated content throughout integrates new knowledge that has emerged since publication of the previous edition.''',
      link:
          'http://93.174.95.29/main/2241000/3d26cda1e839638d1c9db2862ae98270/Andre%20V.%20Ritter%20-%20Sturdevant%E2%80%99s%20Art%20and%20Science%20of%20Operative%20Dentistry-Mosby%20%282018%29.pdf'),
  Book(
      id: 299,
      subject: 'conservative dentistry',
      title:
          'Understanding Dental Caries : From Pathogenesis to Prevention and Therapy',
      writer: 'Michel Goldberg  (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41tYNc-7hCL._SX350_BO1,204,203,200_.jpg',
      rating: 3.1,
      description:
          '''This book thoroughly explains the biological background of dental caries and the formation of carious lesions, providing the reader with a sound basis for understanding the role and effectiveness of different therapeutic and preventive measures. Detailed information is presented on pathogenesis, ultrastructure, and diagnosis. All aspects of the carious process are covered, including development of the initial carious lesion limited to the enamel, evolution of the enamel carious lesion toward a dentin carious lesion, superficial and deep dentin lesions, and cervical erosions. Strategies for prevention and dental tissue regeneration are elaborated and both conventional therapies and minimally invasive and non-invasive treatment approaches are discussed. A separate section is devoted to dental fluorosis and the use of fluoridation and remineralisation agents. This scientifically focused and clinically relevant book, written by acknowledged experts in the field, will appeal to dentists seeking to extend their knowledge as well as to researchers, dental students, and other dental professionals.''',
      link:
          'http://93.174.95.29/main/1533000/ddcd4bbf4cc39ab58674a20b1dbfcd91/Michel%20Goldberg%20%28eds.%29%20-%20Understanding%20Dental%20Caries_%20From%20Pathogenesis%20to%20Prevention%20and%20Therapy-Springer%20International%20Publishing%20%282016%29.pdf'),
  Book(
      id: 300,
      subject: 'conservative dentistry',
      title: 'Essentials of Dental Caries',
      writer: 'Edwina Kidd (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/31tw3wtKy7L._SX331_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Dental caries (tooth decay) is one of the most highly prevalent disease around the world affecting a significant proportion of the population. Dental caries may take place on any tooth surface in the oral cavity where dental plaque is allowed to develop over a period of time. Understanding its causes and progression allows the dental team to prevent and manage it so that patients can maintain healthy teeth for life.

The fourth edition of Essentials of Dental Caries provides readers with an up-to-date, clinically relevant guide to dental caries. Written in an accessible style, the authors explain the biological and socioeconomic background of lesion development and progress. Current methods of clinical diagnosis and evidence based management are outlined in clearly laid out and highly illustrated chapters. This book is essential reading for students and practitioners of dentistry, dental therapy, dental hygiene, and oral health educators.''',
      link:
          'http://93.174.95.29/main/521000/9c94983f098964cc84ff39c93e1efa73/Edwina%20A.%20M.%20Kidd%20-%20Essentials%20of%20Dental%20Caries_%20The%20Disease%20and%20Its%20Management-Oxford%20University%20Press%2C%20USA%20%282005%29.pdf'),
  Book(
      id: 301,
      subject: 'conservative dentistry',
      title: 'Pickard’s Manual of Operative Dentistry',
      writer: 'Avijit Banerjee  (Author), Timothy F. Watson (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51qzSgtI8ZL._SX397_BO1,204,203,200_.jpg',
      rating: 3.6,
      description:
          '''It is vital for modern dentists to appreciate the effects of disease on the dental tissues and the science underpinning the materials that they use in order to maximize restoration success and longevity. Their interaction in this book catalyses the development of the operative skills required to prepare and restore teeth effectively.

The 9th edition of this classic dental textbook has been extensively re-worked, re-styled, and updated to keep abreast of current knowledge, principles, and the modern practice of operative dentistry. The book describes, in a clear and structured manner, the causes of dental disease, methods of identifying the disease process in our patients, and the development and execution of patient-centred management strategies based on disease control and lesion prevention. Common operative procedures and techniques are explained in concise bulleted points, tables, and flowcharts and illustrated in full colour.

The authors are world-renowned experts in the field of Cariology, Minimally Invasive Dentistry, and Dental Biomaterials. New chapters on patient management, disease diagnosis, and risk assessment, with the correlation of dental histology and the material chemistry, combine in this new edition to provide a unique insight into the contemporary world of Operative Dentistry.

This book is the ideal support, at all undergraduate levels, for dental undergraduates and dental care professionals (e.g. therapists) and will act as a solid reference for further post-graduate education.

· The perfect companion for the undergraduate about to embark on their operative dental training
· Profusely illustrated descriptions of operative procedures
· Unique blend of histology and dental materials science

Online Resource Centre
The Online resource Centre to accompany Pickard\'s Manual of Operative Dentistry features:

For registered adopters of the book:
· Figures from the book, available to download''',
      link:
          'http://93.174.95.29/main/1405000/46cdaa6e9cac5a5bca21f4d1ec52b44b/Avijit%20Banerjee%2C%20Timothy%20F.%20Watson%20-%20Pickard%27s%20Manual%20of%20Operative%20Dentistry-Oxford%20University%20Press%20%282011%29.pdf'),
  Book(
      id: 302,
      subject: 'conservative dentistry',
      title: 'Caries Management – Science and Clinical Practice',
      writer:
          'Hendrik Meyer-Lueckel (Editor), Hendrik Meyer-Lückel (Editor), Sebastian Paris (Editor), Kim Ekstrand (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/419G7mi4o5L._SX359_BO1,204,203,200_.jpg',
      rating: 3.3,
      description: '''A comprehensive approach to modern caries management

This systematic approach to modern caries management combines new, evidence-based treatment techniques with the scientific underpinnings of caries formation, providing an in-depth review for both clinicians in daily practice and students advancing in the field.

Beginning with patho-anatomic changes in the dental hard tissues, Dental Caries: Science and Clinical Practice goes on to cover non-invasive, minimally invasive, and more aggressive interventions based on each stage of the disease. From microbiology and histology to visual, tactile and radiographic diagnosis, risk assessment, preventive measures, and tooth preservation and treatment strategies, the book is packed with valuable clinical information for all dental practitioners.

Key Features:

Succinctly covers the science behind the disease, with recommendations for treatments based on assessment starting at the microscopic level
Written by a team of leading worldwide authorities on caries treatment and management—and utilizing the International Caries Detection and Assessment System (ICDAS) standard throughout
Covers the newest treatment techniques, including adhesion technology, fissure sealing and infiltration, caries removal, tooth-colored restorations, and more
Demonstrates step-by-step caries procedures in striking, full-color illustrations of adult and pediatric cases
Offers the newest thinking on early prevention and behavioral changes in oral health promotion, including the role of diet and nutrition, biofilm management, fluoride use, population-based approaches, and more
Shifting to the new paradigm of "heal and seal" rather than the more invasive "drill and fill," this beautifully illustrated text puts scientific principles into clinical action for the best results. It is an essential resource for a complete, proactive approach to caries detection, assessment, treatment, management, and prevention in contemporary dental practice.''',
      link:
          'http://93.174.95.29/main/1445000/b5650cdeab83041bd3b269eb6226422d/Meyer-Lueckel%2C%20Hendrik_%20Ekstrand%2C%20Kim%20R._%20Paris%2C%20Sebastian%20-%20Caries%20Management%20-%20Science%20and%20Clinical%20Practice-Thieme%20%282013%29.pdf'),
  Book(
      id: 303,
      subject: 'conservative dentistry',
      title: 'Fundamentals of Operative Dentistry',
      writer:
          'Thomas J. Hilton  (Author, Editor), Jack L. Ferracane (Author, Editor), James Broome (Author, Editor)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Ux%2BqKHv7L._SX386_BO1,204,203,200_.jpg',
      rating: 3.7,
      description:
          '''Over the past two decades, the Fundamentals of Operative Dentistry has become one of the most trusted textbooks on clinical restorative dentistry. By integrating time-tested methods with recent scientific innovation, the authors promote sound concepts for predictable conservative techniques. Now in its fourth edition, this classic text has been completely updated with full-color illustrations throughout and substantial revisions in every chapter to incorporate the latest scientific developments and current research findings. In addition, a new chapters on color study and shade matching address new areas of focus in the preclinical curriculum. A valuable resource for understanding the scientific basis for current treatment options in dentistry.''',
      link:
          'http://93.174.95.29/main/1513000/2a971c5670e5c3097821cae5d30298e0/Thomas%20J.%20Hilton%2C%20Jack%20L.%20Ferracane%2C%20James%20Broome%2C%20Thomas%20J.%20Hilton%2C%20Jack%20L.%20Ferracane%2C%20James%20Broome%20-%20Summitt%E2%80%99s%20Fundamentals%20of%20Operative%20Dentistry_%20A%20Contemporary%20Approach%2C%20Fourth%20Edition-Quintessen.pdf'),
  Book(
      id: 304,
      subject: 'conservative dentistry',
      title: 'Pickard’s Guide to Minimally Invasive Operative Dentistry',
      writer: 'Avit Banerjee (Author), Timothy F. Watson (Author)',
      edition: '10th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51pYUcsfSPL._SX394_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''An ideal introduction to the theory and practical aspects of conservative dentistry, the tenth edition of Pickards\' Guide to Minimally Invasive Operative Dentistry is a must-have text for all dental students, new graduates and oral healthcare professionals alike. Written in an easy to understand and concise style, the authors introduce the essentials of dental disease before outlining how to collect patient information clinically in order to detect, diagnose, plan and deliver care.

Exploring key topics such as disease prevention and control, the principles of minimally invasive operative dentistry, contemporary restorative materials and procedures, this completely up-to-date revised edition integrates a thorough academic grounding for degree examination with an essential preparation for clinical practice for the whole oral healthcare team. Illustrated with step-by-step colour photos, common clinical procedures are clearly set out and labelled for beginners to learn. The tenth edition has been updated to reflect the latest evidence based guidelines for preventitative management and there is a focus on maintaining existing restorations and follow up/long term care.''',
      link:
          'http://93.174.95.29/main/1680000/76de533a850bd45dfd4832c679edb2b4/Banerjee%2C%20Avijit_%20Watson%2C%20Timothy%20F%20-%20Pickard%27s%20guide%20to%20minimally%20invasive%20operative%20dentistry-Oxford%20University%20Press%20%282015%29.pdf'),
  Book(
      id: 305,
      subject: 'conservative dentistry',
      title: 'Textbook of Preclinical Conservative Dentistry',
      writer: 'Garg (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/518zrU%2BzhjL._SX384_BO1,204,203,200_.jpg',
      rating: 3.9,
      description: '''''',
      link:
          'http://93.174.95.29/main/915000/de984e0d2070141c85e1eb38066608d6/Nisha%20Garg%2C%20Amit%20Garg%20-%20Textbook%20of%20Preclinical%20Conservative%20Dentistry-Jaypee%20Brothers%20%282011%29.pdf'),
  Book(
      id: 306,
      subject: 'conservative dentistry',
      title: 'ADVANCED OPERATIVE DENTISTRY',
      writer:
          'David Ricketts BDS Hons MSc Dist PhD FDS RCS (Eng) FDS Rest Dent FDS RCPS (Glas) FHEA (Author), David W. Bartlett BDS PhD (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51q-fyMRpzL._SX382_BO1,204,203,200_.jpg',
      rating: 3.2,
      description:
          '''Advanced Operative Dentistry: A Practical Approach is a brand new volume that addresses the use of fixed prosthodontics in a single handy reference source.

Prepared by editors and contributors of international renown, this volume places unique emphasis on the biological basis of effective treatment planning by describing the diagnosis, aetiology, risk assessment and preventive management of diseases and disorders and how these factors are integral to predictable long-term patient outcomes.

Advanced Operative Dentistry: A Practical Approach also gives clear advice on the selection and use of modern dental materials and describes how teeth are prepared – and to what extent – for indirect restorations such as crowns, bridges, veneers, inlays and onlays. The book also explores the use of complex indirect fixed prosthodontics which brings with it specific issues of restoration design, retention and occlusal management.

Clearly written and evidenced-based throughout, this practical full colour step-by-step guide will be ideal for undergraduate dental students, vocational trainees and practitioners undertaking post-graduate exams worldwide.

Prepared by editors and contributors of international renown
Contains an abundance of full colour, clinical illustrations to show the results that can be achieved in real life
Describes how to achieve the best appearance in order to meet increasing patient expectations
Discusses the use of fixed prosthodontics in one volume and how fixed and removable prosthodontics can be integrated
Gives unique emphasis on the preventative, biological approach to the use of fixed prosthodontics in order to ensure positive long-term treatment outcomes
Clearly illustrates why aspects of tooth preparation are necessary and how the construction of restorations influences their fit
Provides an integrated, multidisciplinary step-by-step guide to the provision of indirect fixed restorations
Provides guidance on effective communication with laboratory staff to ensure high-quality tooth preparation
Describes the correct handling of materials and restorations when being fitted
Presents the latest findings regarding the use of contemporary materials and techniques – such as the use of Expasyl, Protemp temporary crowns, CAD and CAM crowns
Comprehensive coverage of the subject area makes cross-referencing to other books unnecessary''',
      link:
          'http://93.174.95.29/main/1111000/f7f893093d40a940a8380d5192524c59/%20-%20Advanced%20Operative%20Dentistry-Churchill%20Livingstone%20%282011%29.pdf'),
  Book(
      id: 307,
      subject: 'Orthodontics',
      title: 'Orthodontics, The Art and Science',
      writer: 'Bhalajhi',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51%2Bg-hokH8L._SX440_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1XvYRfdzRDmJSpDOcycJsJFXU3_GqYVEW'),
  Book(
      id: 308,
      subject: 'Orthodontics',
      title: 'Essential Orthodontics (Essentials (Dentistry))',
      writer:
          'Birgit Thilander (Author), Krister Bjerklin (Author), Lars Bondemark (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51zK54KRi9L._SX382_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''Essential Orthodontics is a comprehensive introduction to the biological principles of orthodontics. This book covers the why, when and how of orthodontics, enabling readers to identify which individuals need to be treated, to diagnose based on individual dentofacial development, and to understand the mechanical principles and tissue responses involved.

Divided into three parts, this authoritative resource covers pretreatment considerations, treatment principles of skeletal and dentoalveolar anomalies, and tissue response to orthodontic and orthopaedic forces. Classification of malocclusions and craniofacial growth and development are discussed, and the text explores how to distinguish between normal occlusion and malocclusions. Essential Orthodontics outlines how to perform a comprehensive orthodontic examination leading to an orthodontic diagnosis, and the formation of a treatment plan.
Following a student-friendly layout with key objectives and chapter summaries, Essential Orthodontics is an accessible yet comprehensive resource for both undergraduate and postgraduate dental students.''',
      link:
          'https://drive.google.com/uc?export=download&id=1d7s24V6k9PIlTppG8ysLNVSwwxEVLMe8'),
  Book(
      id: 309,
      subject: 'Periodontology',
      title: 'Carranza\'s Clinical Periodontology: Second South Asia Edition',
      writer:
          'Chini Doraiswami Dwarakanath (Author), N Ambalavanan (Editor), Dilip G Nayak (Editor), Ashita Uppoor (Editor), Ashish Jain (Editor)',
      edition: '11th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/517LLdB7UCL._SX380_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''Completely and comprehensively revised and updated
International experts cover every aspect of periodontology
Superb graphics and high technology print design makes it easy to read
Periodontal pathology atlas containing the most comprehensive high quality image collection
Coverage of the latest advances includes the emerging link between periodontal disease and systemic health
Serves as an excellent foundation in preparing for the National Board Dental Exam
Contains 6 additional chapters earlier available online on Expert Consult:
Introduction to Evidence-Based Decision Making
Assessing Evidence
Implementing Evidence-Based Decision in Clinical Practice
Legal Principles: Jurisprudence
Dental Insurance and Managed Care in Periodontal Practice
Lesions of Oral Mucosa, Bone, and Other Structures
Some useful topics/chapters of CP 10/e are also added in the book:
Immunity and Inflammation: Basic Concepts
Microbial Interactions with the Host in Periodontal Diseases
Advanced Diagnostic Techniques
Dental Ethics
Periodontal Index
Completely and comprehensively revised and updated
International experts cover every aspect of periodontology
Superb graphics and high technology print design makes it easy to read
Periodontal pathology atlas containing the most comprehensive high quality image collection
Coverage of the latest advances includes the emerging link between periodontal disease and systemic health
Serves as an excellent foundation in preparing for the National Board Dental Exam
Contains 6 additional chapters earlier available online on Expert Consult:
Introduction to Evidence-Based Decision Making
Assessing Evidence
Implementing Evidence-Based Decision in Clinical Practice
Legal Principles: Jurisprudence
Dental Insurance and Managed Care in Periodontal Practice
Lesions of Oral Mucosa, Bone, and Other Structures
Some useful topics/chapters of CP 10/e are also added in the book:
Immunity and Inflammation: Basic Concepts
Microbial Interactions with the Host in Periodontal Diseases
Advanced Diagnostic Techniques
Dental Ethics
Periodontal Index''',
      link:
          'https://drive.google.com/uc?export=download&id=1YQ9biTQJ9KUDkSdCLAkwkBgdMeeAg-FB'),
  Book(
      id: 310,
      subject: 'Periodontology',
      title: 'Carranza\'s Clinical Periodontology: Second South Asia Edition',
      writer:
          'Chini Doraiswami Dwarakanath (Author), N Ambalavanan (Editor), Dilip G Nayak (Editor), Ashita Uppoor (Editor), Ashish Jain (Editor)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41dQCrNj6AL._SX382_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''Carranza\'s Clinical Periodontology: Second South Asia Edition is a complete and thorough presentation of periodontology essentials while retaining the style and quality that makes the book the number one periodontal textbook in the world.

The gold standard since 1947, Carranza’s Clinical Periodontology is more than just a textbook, it features expert leadership, an improved organization, and new online features. It describes techniques in reconstructive, esthetic, and implant therapy, and explains the evidence supporting each treatment. Renowned authorities help you learn the fundamentals, make the best clinical decisions, get the best results from each procedure, avoid complications, and exceed your patients\' expectations.

Over 1650 images in the book beautifully illustrate the details of specific conditions and treatments.
Though the basic concepts remain the same, the sections on Tooth brush design, Dentifrices and Chemical plaque biofilm control with oral rinses in the chapter ‘Plaque Biofilm Control’ have been totally revamped to include more details for better understanding. Additionally, classification of Chemical plaque control agents which was not there in earlier editions has also been included.
Since the book is targeted for UG students, only the pertinent and basic concepts of Implantology have been retained in print form, the rest have been made available online.
Comprehensive coverage includes the etiology and treatment of periodontal diseases, the relationship between periodontal disease and systemic health, and oral implant dentistry
The book comes with complimentary access to enhanced e-book with additional reads on:

The Historical Background of Periodontology
Molecular Biology of Host-Microbe Interactions
Gingival Disease in Childhood
Desquamative Gingivitis
Necrotizing Ulcerative Periodontitis
Masticatory System Disorders that Influence the Periodontium
Sleep-Disordered Breathing
Significance of Clinical and Biologic Information
Conscious Sedation
Periodontal Therapy in the Female Patient
Periodontal Treatment for Older Adults
Occlusal Evaluation and Therapy
Multidisciplinary Approach to Dental and Periodontal Problems
Results of Periodontal Treatment
Atlas of Periodontal Diseases
Electronic Dental Records and Decision Support Systems
Locally Delivered, Controlled-Release Antimicrobials: Drug Development and Clinical Research''',
      link:
          'https://drive.google.com/uc?export=download&id=1YQ9biTQJ9KUDkSdCLAkwkBgdMeeAg-FB'),
  Book(
      id: 311,
      subject: 'Public Health Dentistry',
      title: 'A Textbook Of Public Health Dentistry Paperback',
      writer: 'CM Marya',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41DlrNqDKEL._SX373_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1YmQffL_4AQ8UwUtLbFqEZkBzHzv24q1Z'),
  Book(
      id: 312,
      subject: 'Forensic Dentistry',
      title: 'Manual of Forensic Odontology',
      writer: 'David R. Senn (Editor), Richard A. Weems (Editor)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51dZPPLvZQL._SX357_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Advances in forensic odontology have led to improvements in dental identification for individual cases as well as in disaster victim identification (DVI). New and updated technologies mean advances in bitemark analysis and age estimation. Growth in the field has strengthened missing persons’ networks leading to more and faster identifications of unidentified individuals.

A product of the American Society of Forensic Odontology, the Manual of Forensic Odontology, Fifth Edition provides comprehensive and up-to-date information involving all facets of forensic dentistry and explores critical issues relating to the scientific principles supporting the field’s evaluations and conclusions.

New information in the Fifth Edition includes

Scientific principles and the need for more and better research in the field
Oral and maxillofacial radiographic features of forensic interest
Forensic pathology and its ties to forensic odontology
New techniques and improved technologies for age estimation
Advances in bitemark evidence management
Animal bitemarks
National and international forensic dental organizations
Tips for becoming involved in forensic odontology
The manual has been an important source of forensic dentistry information for more than 20 years. This new edition is edited by a past president of the American Board of Forensic Odontology and a past Chair of the Odontology Section of the American Academy of Forensic Sciences. Expanded and enhanced with extensive color illustrations, this volume is designed to provide essential information based on sound scientific principles for experienced forensic odontologists and for those new to the discipline.''',
      link: ''),
  Book(
      id: 313,
      subject: 'Forensic Dentistry',
      title: 'Review of Forensic Medicine and Toxicology',
      writer:
          'Gautam Biswas  (Author), Joseph A. Prahlow (Foreword), Anil Aggrawal (Foreword)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51CWh3VdZsL._SX363_BO1,204,203,200_.jpg',
      rating: 2.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1t8HoMlsRmIW2gaDcGrGZoNYDr4g8xDSb'),
  Book(
      id: 314,
      subject: 'Forensic Dentistry',
      title: 'Simpson’s Forensic Medicine',
      writer: 'Richard Jones (Author), Steven B Karch (Author)',
      edition: '12th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51WfnJ98f-L._SX381_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''Since the first edition was published in 1947, Simpson\'s Forensic Medicine has become the classic introduction to forensic medicine and pathology. Written by one of the leading forensic pathologists in the field, this new edition is completely up-to-date and revised to include information on living subjects.''',
      link:
          'https://drive.google.com/uc?export=download&id=1tFJBbx3bfCC1lB8nE6nC5xqSNxVLVZxR'),
  Book(
      id: 315,
      subject: 'Forensic Dentistry',
      title: 'The essential of forensic medicine & toxicology',
      writer: 'Reddy Narayan (Author)',
      edition: '33th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51WkIkQi-ZL._SY498_BO1,204,203,200_.jpg',
      rating: 3.9,
      description: '''Entirely revised and updated with medicolegal cases. 
• Concise, easy-to-grasp and streamlined presentation. 
• Illustrated with diagrams, photographs, tables and important points. 
• Important topics are dealt in detail to meet the requirements of
medical officers such as Forensic Ballistics, Regional Injuries, Anesthetic and Operative Deaths, DNA Fingerprinting and
Blood Stains, etc. 
• A few new topics, such as procedure to be followed in dealing
with medicolegal cases, virtual autopsy have been incorporated. 
• Text printed in smaller type is meant for medical officers
undertake medicolegal work, medical practitioners, members of
the legal profession and other law enforcement officers. 
• Must-have for undergraduate medical students, postgraduate
students, medical teachers and officers and lawyer.''',
      link:
          'https://drive.google.com/uc?export=download&id=1X3HYnW0TPz6GPFECZScBbyc05jQHeGeq'),
  Book(
      id: 316,
      subject: 'Forensic Dentistry',
      title: 'Color Atlas of the Autopsy',
      writer: 'Scott A. Wagner (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51%2BaFFxe7YL._SX366_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''Standing over the autopsy table gives you an unparalleled perspective on every element of the autopsy procedure. Remarkable details of disease and injury appear right before your eyes, presenting a complete picture that leads you in the direction of death. Now, those striking images have been taken from the table to the text in the only full-color guide to all aspects of the autopsy.

Forensic pathology is a visual discipline, making images essential to properly explaining the critical process. Featuring over 500 full-color photographs, Color Atlas of the Autopsy provides unadulterated access to every probe of the autopsy procedure. As the only atlas to focus on autopsy protocol, the book introduces the process and principles of the procedure to uninitiated professionals who interact with the pathologist before, during, and after the autopsy. This incomparable guide presents an astonishing visual experience that goes beyond a demonstration to demystify the autopsy.''',
      link:
          'https://drive.google.com/uc?export=download&id=1lQC6QFMRtg9rfhAGgyqU2L48bhsJubhU'),
  Book(
      id: 317,
      subject: 'Forensic Dentistry',
      title: 'Forensic Dentistry',
      writer: 'David R. Senn, Paul G. Stimson',
      edition: '2nd',
      image:
          'https://images.tandf.co.uk/common/jackets/amazon/978142007/9781420078367.jpg',
      rating: 4.9,
      description:
          '''The identification of unknown individuals and the estimation of age, race, and gender are among the chief functions of forensic dentistry. Other important applications include the investigation and analysis of bitemarks and oral injuries in abuse cases and evaluating, reporting, and testifying in civil litigation cases. Twelve years after the benchmark first edition of this book explored these topics, the long-awaited Forensic Dentistry, Second Edition offers a comprehensive update and revision of the material.

Offering insight from many new contributors on the cutting edge of forensic science and odontology, this new edition expands the book’s scope to include a broader historical and theoretical analysis, a thorough assessment of the past decade’s developments, and a far-reaching projection of future trends.

New topics in the second edition include:

Forensic dental radiography
Age estimation
Jurisprudence and legal issues
History of forensic dentistry
Landmark cases, including September 11th and Hurricane Katrina
In order for forensic odontology to continue to progress as a specialty of forensic science, there must be a consistent stream of new ideas and original and applied research. Heavily illustrated and enhanced with a 16-page color insert with additional photos, this volume captures the critical issues that confront today’s forensic dentist, explores the field’s limitations, and provides a window on the future of this crucial sector within the forensic identification science arena.''',
      link:
          'https://drive.google.com/uc?export=download&id=1GdxFQ4lNGF-UW6z0sWPJdnqQRhL4nFHX'),
  Book(
      id: 318,
      subject: 'Forensic Dentistry',
      title: 'Evidence Based Forensic Dentistry',
      writer: 'Balwant Rai (Author), Jasdeep Kaur (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41MBaXLBDvL._SX350_BO1,204,203,200_.jpg',
      rating: 3.1,
      description:
          '''Recent years have witnessed significant advances in forensic odontology. This book presents basic concepts in the field and describes all the standard examination procedures currently employed in the acquisition of dental evidence. Detailed information is provided on the identification of unknown individuals, the application of forensic dentistry in mass disasters and multiple fatality incidents, the role of dental evidence in child abuse investigations, and the analysis of bite mark evidence. Other features of the book are a series of high-profile cases, clear advice on the writing of legal reports, and discussion of the significance of DNA and oral fluid in forensic odontology. The text is supplemented by numerous high-quality figures, many of them in color. This book will be invaluable for dental examiners and pathologists, legal and police science professionals, and dentists who want to use their training and experience in an interesting and challenging way.''',
      link:
          'http://93.174.95.29/main/1033000/7ea94415dd679cef804352d77eae2ac9/Balwant%20Rai%2C%20Jasdeep%20Kaur%20%28auth.%29%20-%20Evidence-Based%20Forensic%20Dentistry-Springer-Verlag%20Berlin%20Heidelberg%20%282013%29.pdf'),
  Book(
      id: 319,
      subject: 'Forensic Dentistry',
      title: 'Forensic and Legal Dentistry',
      writer: 'Klaus Rötzscher (Editor)',
      edition: '2014th Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41DmPOfBmSL._SX330_BO1,204,203,200_.jpg',
      rating: 3.0,
      description:
          '''This book both explains in detail diverse aspects of the law as it relates to dentistry and examines key issues in forensic odontostomatology. A central aim is to enable the dentist to achieve a realistic assessment of the legal situation and to reduce uncertainties and liability risk. To this end, experts from across the world discuss the dental law in their own countries, covering both civil and criminal law and highlighting key aspects such as patient rights, insurance, and compensation. In the section on forensic odontostomatology, extensive guidance is provided on development of the dentition, clinical findings and documentation, personal identification, age estimation, and the nature and significance of bite, tooth, and lip marks. This book will be an invaluable source of information for all who practice in the field of dentistry as well as forensic scientists, lawyers, investigative and identification authorities, criminologists, prosecutors, insurance agents, and students.''',
      link:
          'http://93.174.95.29/main/1132000/46ec3479769d726deef4cfb15012eef8/Klaus%20R%C3%B6tzscher%20%28auth.%29%2C%20Klaus%20R%C3%B6tzscher%20%28eds.%29%20-%20Forensic%20and%20Legal%20Dentistry-Springer%20International%20Publishing%20%282014%29.pdf'),
  Book(
      id: 320,
      subject: 'Forensic Dentistry',
      title: 'Forensic Odontology : Principles and Practice',
      writer: 'Jane Taylor (Editor), Jules Kieser (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/519U4iJAAeL._SX346_BO1,204,203,200_.jpg',
      rating: 3.4,
      description:
          '''Forensic odontology refers to the science and practice of dentistry which may be applied to help solve litigation in both criminal and civil cases. It is a specialist branch of dentistry that assists the legal system in the handling, analysis and interpretation of dental evidence.

Forensic Odontology: Principles and Practice pulls together the very latest research findings and advice on best practice and essential skills, including aspects of forensic science that provide a well-rounded educational experience for the reader. Chapters provide coverage of anatomy and morphology, mortuary techniques, physical anthropology, applied forensic sciences, child and elder abuse, and facial approximation. The text introduces the various topics and discusses underpinning philosophies without being an exhaustive historical treatise. Appropriate case studies are used to highlight issues, and references to current research are provided to stimulate further reading and research.

Written by experienced practitioners in the field, this informative introductory text is invaluable to graduate and undergraduate students, as well as experienced dentists, wishing to gain experience or pursue a career in forensic odontology. This text will be a welcome addition to the forensic odontological libraries of all practicing forensic odontologists.''',
      link:
          'http://93.174.95.29/main/1594000/912a6173dd981635682653e169f5dbbb/Jane%20Taylor%2C%20Jules%20Kieser%20-%20Forensic%20Odontology_%20Principles%20and%20Practice-Wiley-Blackwell%20%282016%29.pdf'),
  Book(
      id: 321,
      subject: 'Forensic Dentistry',
      title: 'Forensic Odontology: An Essential Guide',
      writer:
          'Catherine Adams (Author), Romina Carabott (Author), Sam Evans (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41R7kE3jrxL._SX336_BO1,204,203,200_.jpg',
      rating: 3.2,
      description:
          '''An accessible, essential introduction to forensic odontology. 

Written by a team of well-established, active practitioners in the field, Forensic Odontology is invaluable for those needing an introduction to the subject for the general dental practitioner who has an interest in forensic dentistry and is contemplating practicing in the field. It will also be useful as a reference during practice. 

After a brief introduction the book covers dental anatomy and development, expert witness skills, mortuary practice, dental human identification, disaster victim identification, dental age assessment, bite marks, forensic photography and the role of the forensic odontologist in protection of the vulnerable person. Chapters outline accepted and recommended practices and refer to particular methodologies, presenting different schools of thought objectively.''',
      link:
          'http://93.174.95.29/main/1168000/96ad3aac20ec1f60262b99b7f7c03927/Catherine%20Adams%2C%20Romina%20Carabott%2C%20Sam%20Evans%20-%20Forensic%20Odontology_%20An%20Essential%20Guide-Wiley-Blackwell%20%282014%29.pdf'),
  Book(
      id: 322,
      subject: 'Forensic Dentistry',
      title: 'Forensic Dental Evidence: An Investigator’s Handbook',
      writer: 'C. Michael Bowers  (Editor)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/513b5%2BOdT7L._SX403_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Forensic Dental Evidence: An Investigators Handbook highlights the discussion regarding unjust convictions caused by inaccurate bitemark opinions. The book focuses on cases that use forensic techniques, emphasizing modern methods and protocols. Through this book, the latest information available is offered to the forensic community.

This book demonstrates expertise in forensic dentistry by presenting chapters on human identification in domestic and international situations; investigations on missing person and violent crimes against persons; mass-disaster planning and disaster response; and new threats from terrorist attacks on urban centers. Furthermore, it discusses topics regarding bitemark evidence, such as forensic photography, analysis and legal issues. The book also presents two chapters on new scientific topics: The Next Level in Victim Identification: Materials Properties as an Aid in Victim Identification; and DNA for First Responders: Recognizing, Collecting, and Analyzing Biological Evidence Related to Dentistry (chapters 3 and 8, respectively).

This book is suited to anyone seeking knowledge on forensic dentistry; it will be of great value to investigators, lawyers, medical examiners, nurses, and dentists with an interest in forensic dental cases.

Contributions by internationally recognized and experienced forensic experts cover missing persons cases and mass disaster cases from around the world
Contains over 200 full-color photographs of crime scene evidence, human identification cases and bitemark details
Includes many new exoneration cases derived from the Editor\'s work with the Innocence Project''',
      link:
          'http://93.174.95.29/main/737000/39df0e8bbbef94dadebc3a6e8b369f95/C.%20Michael%20Bowers%20-%20Forensic%20Dental%20Evidence_%20An%20Investigator%27s%20Handbook%20%20-Elsevier%20%282011%29.pdf'),
  Book(
      id: 323,
      subject: 'Paediatric Dentistry',
      title: 'Textbook of Pediatric Dentistry',
      writer: 'Nikhil Marwah (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51t-pGM5thL._SX369_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1RNMWVxHYb16d1oMnZw7rQF-olMWEW4ZH'),
  Book(
      id: 324,
      subject: 'Child Health Nursing',
      title:
          'Child Health Nursing: Partnering with Children and Families with Mynursinglab',
      writer:
          'by Ball (Author), Jane W. Ball (Author), Ruth C. Bindler (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51BYnQEdChL._SX383_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1PelMQbSN2AyshAG2KWqAqFCS_dYjQhDb'),
  Book(
      id: 325,
      subject: 'Child Health Nursing',
      title:
          'All-in-One Nursing Care Planning Resource : Medical-Surgical, Pediatric, Maternity, and Psychiatric-Mental Health',
      writer: 'By (author)  Pamela L. Swearingen',
      edition: '3rd',
      image:
          'https://d1w7fb2mkkr3kw.cloudfront.net/assets/images/book/lrg/9780/3232/9780323262866.jpg',
      rating: 4.3,
      description:
          '''The only book with nursing care plans for all core clinical areas, All-In-One Care Planning Resource, 3rd Edition, provides 100 care plans with the nursing diagnoses and interventions you need to know to care for patients in all settings. It includes care plans for pediatric, maternity, and psychiatric nursing in addition to medical-surgical nursing, so you can use just one book throughout your entire nursing curriculum. A new online care plan tutorial walks you through the steps of creating care plans, and updates keep you current with the latest clinical developments, new pharmacologic treatments, QSEN patient safety standards, and evidence-based practice guidelines. Edited by Pamela Swearingen, this book is known for its clear, straightforward approach, its practical and consistent format, and its detailed rationales.



NANDA-I nursing diagnoses are incorporated throughout the text to keep you current with NANDA-I terminology and the latest diagnoses.
Color-coded sections for medical-surgical, maternity, pediatric, and psychiatric-mental health nursing care plans make it easier to find information quickly.
A consistent format for each care plan allows faster lookup of topics, with headings for Overview/Pathophysiology, Health Care Setting, Assessment, Diagnostic Tests, Nursing Diagnoses, Desired Outcomes, Interventions with Rationales, and Patient-Family Teaching and Discharge Planning.
Prioritized nursing diagnoses are listed in order of importance and physiologic patient needs. 
A two-column format for nursing assessments/interventions and rationales makes it easier to scan information.
Detailed rationales for each nursing intervention help you to apply concepts to specific patient situations in clinical practice.
Outcome criteria with specific timelines help you to set realistic goals for nursing outcomes and provide quality, cost-effective care.



NEW! Care plan for normal labor and birth addresses nursing care for the client experiencing normal labor and delivery.
UPDATED content is written by practicing clinicians and covers the latest clinical developments, new pharmacologic treatments, patient safety considerations, and evidence-based practice guidelines.
NEW full-color design makes the text more user friendly, and includes NEW color-coded tabs and improved cross-referencing and navigation aids for faster lookup of information.
NEW! Leaf icon highlights coverage of complementary and alternative therapies including information on over-the-counter herbal and other therapies and how these can interact with conventional medications.''',
      link:
          'https://drive.google.com/file/d/1i7DKWHr6QlEOb2AA23W7dYBAaTrbwCl9/view?usp=sharing'),
  Book(
      id: 326,
      subject: 'Child Health Nursing',
      title: 'Lecture note for Pediatrics Nursing',
      writer: 'EPHTI',
      edition: '',
      image:
          'https://s.pdfdrive.com/assets/thumbs/319/3191ff8e6edbc0f2e572bcaca5da860c.jpg',
      rating: 5.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1sGXIL2zTDYeMM56PtrT-kdQMEPxFiuLI'),
  Book(
      id: 327,
      subject: 'Child Health Nursing',
      title: 'Pediatric Nursing Demystified (Demystified Nursing)',
      writer: 'Johnson, Joyce Published by McGraw-Hill Professional',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/516vVHGPwiL._SX395_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=13c-HtgKwOxSkvKsh8ys0O9vFWD96PLi3'),
  Book(
      id: 328,
      subject: 'Child Health Nursing',
      title:
          'Maternal and Child Health Nursing: Care of the Childbearing and Childrearing Family',
      writer: 'Adele Pillitteri  (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/411yrmMYl9L._SX367_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''Now in a fully revised, updated Fifth Edition, this text helps nurses understand wellness and illness as family-centered events. Using a nursing process framework, the book presents information in a clear, reader-friendly fashion.

Each chapter begins with Key Terms, Learning Objectives, and a Case Study and ends with Key Points and Critical Thinking Exercises. New to this edition are Focus on Nursing Care Planning: Multidisciplinary Care boxes, which guide nurses in working with other healthcare providers. Other features include NIC and NOC, Focus on Pharmacology, Focus on Communication, and Assessing the Client boxes, "What If" questions, and illustrated nursing procedures.''',
      link:
          'http://93.174.95.29/main/260000/c1b6ff63c2600270963d6ff9d8a3d4bf/%28Point%29%20Adele%20Pillitteri%20-%20Maternal%20and%20Child%20Health%20Nursing_%20Care%20of%20the%20Childbearing%20and%20Childrearing%20Family-Lippincott%20Williams%20%26%20Wilkins%20%282006%29.chm'),
  Book(
      id: 329,
      subject: 'Child Health Nursing',
      title:
          'Child and Adolescent Behavioral Health: A Resource for Advanced Practice Psychiatric and Primary Care Practitioners in Nursing',
      writer:
          'Edilma L. Yearwood (Editor), Geraldine S. Pearson (Editor), Jamesetta A. Newland (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51h0iaFTPlL._SX384_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''As an increasing number of children and adolescents with psychiatric symptoms go unrecognized in our current healthcare system, the ability to identify and treat these issues in multiple healthcare settings has become vitally important. With access to primary care providers increasing and a shortage of child psychiatric providers, collaboration between psychiatric, pediatric and family advanced practice nurses is essential to improving care for this vulnerable population. Child and Adolescent Behavioral Health provides a practical reference to aid in this endeavour. Written and reviewed by over 70 nurse experts, it is a must-have reference for all practitioners caring for children and adolescents.''',
      link:
          'http://93.174.95.29/main/2373000/0cd7799d915ad62c89721d6eceec1b19/Edilma%20L.%20Yearwood_%20Geraldine%20S.%20Pearson%20-%20Child%20and%20Adolescent%20Behavioral%20Health_%20A%20Resource%20for%20Advanced%20Practice%20Psychiatric%20and%20Primary%20Care%20Practitioners%20in%20Nursing-Wiley-Blackwell%20%282012%29.pdf'),
  Book(
      id: 330,
      subject: 'Child Health Nursing',
      title: 'Child health nursing: partnering with children and families',
      writer:
          'Ball DrPH RN CPNP, Jane W. (Author), Ruth C. Bindler (Author), Kay J. Cowen (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/61%2BsHRK3d-L._SX400_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''This extensively-updated text is designed to promote excellence in pediatric nursing care, in both acute care settings and in the community. CHILD HEALTH NURSING, 3/e focuses on helping students synthesize new knowledge, apply evidence-based findings, collaborate with children, families, and other healthcare professionals, and use clinical reasoning to plan superior care. It views families as integral participants in all care, and recognizes that all children need health promotion and maintenance interventions, wherever they seek care or whatever conditions they are experiencing. This edition uses current NANDA International diagnoses, Nursing Intervention Classifications (NIC), Nursing Outcomes Classifications (NOC), and Healthy People 2020 recommendations. Sample nursing care plans help students apply developmental, psychosocial, and physiologic concepts to the care of children with specific conditions. Research, clinical reasoning, and evidence-based practice are emphasized and integrated throughout, and coverage of contemporary topics ranges from genomics to new pharmacological treatment options.''',
      link:
          'http://93.174.95.29/main/1606000/214f43e23070839210ae42cefdf1bf5a/Jane%20W.%20Ball%2C%20Ruth%20C.%20Bindler%2C%20Kay%20J.%20Cowen%20-%20Child%20health%20nursing_%20partnering%20with%20children%20and%20families-Pearson%20%282014%29.epub'),
  Book(
      id: 331,
      subject: 'Communication and Educational Technology',
      title:
          'Nurse as Educator - Principles of Teaching and Learning for Nursing Practice',
      writer: 'Susan B. Bastable',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51OyN4QA3GL._SX383_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1qgpZZqC4n47FqQYvwViwp42igEVvVzP_'),
  Book(
      id: 332,
      subject: 'Community Health Nursing',
      title: 'Community and Public Health Nursing',
      writer:
          'David Sines (Editor), Sharon Aldridge-Bent (Editor), Agnes Fanning (Editor), Penny Farrelly (Editor), Kate Potter (Editor)',
      edition: '5th',
      image: 'https://images-eu.ssl-images-amazon.com/images/I/41z8ACpHUWL.jpg',
      rating: 4.7,
      description:
          '''"An extremely popular and valuable resource to students, practitioners and managers in community health care nursing" - Journal of Advanced Nursing

The fifth edition of Community and Public Health Nursing is an essential source of information for all those working in primary and community healthcare.  Comprehensive and accessible, it draws on the knowledge of a wide range of experts and conveys all the information and skills nurses working in modern primary care settings require. It includes material on policy developments, research perspectives, health visiting, practice and district nursing, team working, advanced nursing practice, non-medical prescribing, inter-professional practice, and user involvement.

New edition of the definitive textbook on community healthcare nursing
Covers learning disability nursing, caring for patients with mental health conditions, and community children’s nursing and school nursing
Written by experts in the field – providing authority and insight
Thorough, comprehensive, and up-to-date with the latest policy guidelines
Community and Public Health Nursing is an invaluable resource for novice and experienced practitioners, and for all healthcare professionals who work in the primary care and community setting, including practice nurses, nurse practitioners, district nurses, community staff nurses, health visitors, school nurses, walk-in centre nurses and sexual health nurses.''',
      link:
          'https://drive.google.com/uc?export=download&id=1A__K4GIX4Hg1zY9stO7psZNMhtQx34zY'),
  Book(
      id: 333,
      subject: 'Community Health Nursing',
      title:
          'Community & Public Health Nursing: Promoting the Public\'s Health',
      writer:
          'Judith Allender RN C MSN EdD (Author), Cherie Rector PhD RN C (Author), Kristine Warner PhD MS MPH RN (Author)',
      edition: '8th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51B28iW2QiL._SX383_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1y-Az4xw7jpo44pLBOCRtih0GAmTL5CJT'),
  Book(
      id: 334,
      subject: 'Community Health Nursing',
      title:
          'Public Health Nursing: Population-Centered Health Care in the Community',
      writer:
          'Marcia Stanhope RN DSN FAAN (Author), Jeanette Lancaster RN PhD FAAN (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51UZWzmx%2BTL._SX390_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''Prepare for a successful career as a community/public health nurse! Public Health Nursing: Population-Centered Health Care in the Community, 9th Edition provides up-to-date information on issues that impact public health nursing, such as infectious diseases, natural and man-made disasters, and health care policies affecting individuals, families, and communities. Real-life scenarios show examples of health promotion and public health interventions. New to this edition is an emphasis on QSEN skills and an explanation of the influence of the Affordable Care Act on public health. Written by well-known nursing educators Marcia Stanhope and Jeanette Lancaster, this comprehensive, bestselling text is ideal for students in both BSN and Advanced Practice Nursing programs.

Evidence-Based Practice and Cutting Edge boxes illustrate the use and application of the latest research findings in public/community health nursing.
Healthy People 2020 boxes highlight goals and objectives for promoting the nation’s health and wellness over the next decade.
Levels of Prevention boxes identify specific nursing interventions at the primary, secondary, and tertiary levels.
Practice Application scenarios help you apply chapter content to the practice setting by analyzing case situations and answering critical thinking questions.
Linking Content to Practice boxes provide examples of the nurse’s role in caring for individuals, families, and populations in community health settings.
Unique! Separate chapters on healthy cities, the Minnesota Intervention Wheel, and nursing centers describe different approaches to community health initiatives.
Community/Public Health Nursing Online consists of 14 modules that bring community health situations to life, each including a reading assignment, case scenarios with learning activities, an assessment quiz, and critical thinking questions. Sold separately.
NEW! Coverage of health care reform discusses the impact of The Patient Protection and Affordable Care Act of 2010 (ACA) on public health nursing.
NEW! Focus on Quality and Safety Education for Nurses boxes give examples of how quality and safety goals, knowledge, competencies and skills, and attitudes can be applied to nursing practice in the community.''',
      link:
          'https://drive.google.com/uc?export=download&id=1FHieHY8ZAK8nB0ZRn0YIC_Wq5shNssDt'),
  Book(
      id: 335,
      subject: 'Community Health Nursing',
      title:
          'Community/Public Health Nursing: Promoting the Health of Populations',
      writer:
          'Mary A. Nies PhD RN FAAN FAAHB (Author), Melanie McEwen PhD RN (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51V3ee93YoL._SX389_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1dwhOYDjxqLzWiI8ohdLXtoqUO4n_4xa-'),
  Book(
      id: 336,
      subject: 'Community Health Nursing',
      title:
          'Community & Public Health Nursing: Promoting the Public\'s Health',
      writer: 'Rector PhD RN-C, Cherie (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51BS7tt52cL._SX382_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''This student-friendly, highly visual text expands students’ viewpoints from the client-nurse relationship to a population focus. Acknowledging that population-focused tools and interventions are needed in acute care, as infection rates continue to rise and nurse-sensitive outcome indictors are closely monitored, Cherie Rector weaves in meaningful, real-life examples, case studies, and perspectives to help students understand that transitions in care are critical in today’s healthcare system. Covering a multitude of community and public settings, situations, and populations, the book helps students learn about promoting health, preventing disease (not just treating it), and protecting at-risk populations—including the elderly, the LGBT community, and veterans. This fully updated 9th Edition encourages students to think more globally and covers new innovations and emerging threats to the public’s health.

KEY FEATURES
NEW! QSEN sections tie key chapter concepts to quality and safety competencies, such as patient-centered care, teamwork & collaboration, evidence-based practice, quality improvement, and informatics, to help students understand the importance of these concepts.
NEW! Application to Population Health explores chapter concepts from a population-focused viewpoint and offers current examples of effective population interventions.What Do YOU Think? encourages students to reflect on thought-provoking current topics or dilemmas, enhancing critical thinking skills.Evidence-based Practice demonstrates how current research examples can be applied to public/community health nursing practice to achieve optimal outcomes.From the Case Files presents case study scenarios with application-based questions, challenging students to reflect on assessment and intervention.Perspectives from nursing students, novice to expert public health nurses, faculty members, policy makers, and clients cover commonly held misconceptions about community health nursing and link between skills across settings.Healthy People 2020 highlights pertinent goals and objectives to promote health.Activities to Promote Critical Thinking at the end of each chapter challenge students, promote critical-thinking skills, and encourage active involvement in solving community health problems.
Unique Levels of Prevention Pyramid boxes address a chapter topic and describe nursing actions at each of the three levels of prevention to help students understand this basic community health nursing concept.
Content from the text is embedded into two integrated digital learning solutions— Lippincott CoursePoint for pre-licensure programs and Lippincott RN to BSN Online for post-licensure programs—that feature experiential, case-based instructional design aligned with the approach of the Ninth Edition. To learn more about Lippincott CoursePoint and Lippincott RN to BSN Online and to see our Video Cases, please visit http://nursingeducationsuccess.com.''',
      link:
          'http://93.174.95.29/main/2376000/3641b8343a596462d2d66fbf377e50e2/Rector%2C%20Cherie%20L.%20-%20Community%20and%20public%20health%20nursing_%20promoting%20the%20public%E2%80%99s%20health-Wolters%20Kluwer%20%282018%29.pdf'),
  Book(
      id: 337,
      subject: 'English for Nursing',
      title: 'Cambridge English for Nursing Intermediate Plus Student\'s Book',
      writer: 'Virginia Allum  (Author), Patricia McGarr (Author)',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51PRXceSrKL._SX381_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1F88ygGp4rM8PNgFkPiMwTStvdN_Nu2ZI'),
  Book(
      id: 338,
      subject: 'English for Nursing',
      title:
          'Oxford English for Careers: Nursing 1: Oxford English for Careers: Nursing: ELT Level 1: Pre-Intermediate: Student\'s Book',
      writer: 'by Tony Grice  (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51epjDjS8wL._SX377_BO1,204,203,200_.jpg',
      rating: 4.1,
      description: '''''',
      link:
          'http://93.174.95.29/main/772000/c71969b16306771b466deef1bb65a19f/Tony%20Grice%20-%20Oxford%20English%20for%20Careers_%20Nursing%201_%20Oxford%20English%20for%20Careers_%20Nursing_%20ELT%20Level%201_%20Pre-Intermediate_%20Student%27s%20Book%20%20-OUP%20Oxford%20%282007%29.pdf'),
  Book(
      id: 339,
      subject: 'English for Nursing',
      title: 'Everyday English for Nursing',
      writer: 'by Grice BPhil MA CertEd, Tony (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/518CP14EMDL._SX378_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''A specialist U.K. English language learning course book for nurses who are non-native speakers of U.K. English. The book is intended for self study but would serve as a major resource for a taught course.

The book presents examples of formal medical U.K. English, colloquialisms, idioms and clinical notes. The user practices reading and writing through exercises and the language is introduced through the medium of a series of simulated clinical cases

The first part contains text and exercises which are `about\' nursing in the NHS - the crisis, what nurses say about the crisis, the hospital hierarchy, pay and conditions, applying for jobs, etc. The second part is about communication in a simulated hospital setting. At its core are clinical forms relating to admission, patient care and hospital discharge. These forms and clinical documents generate exercises, which practice parts of language (idiomatic phrases, etc.) The book will be highly illustrated assisting with the clarity and understanding of situations/scenarios''',
      link:
          'http://93.174.95.29/main/2041000/704a863474758a61bf7794a479f2ca57/Grice%20Tony.%20-%20Everyday%20English%20for%20Nursing.pdf'),
  Book(
      id: 340,
      subject: 'Management of Nursing Services and Education',
      title: 'AACN Essentials of Critical Care Nursing',
      writer: 'Suzanne M. Burns (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51u9u8uCSmL._SX388_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=11KKf1xmkOsBVKFFsgdKjGsdyNbqs3khI'),
  Book(
      id: 341,
      subject: 'Management of Nursing Services and Education',
      title: 'AACN Essentials of Critical Care Nursing(Pocket Handbook)',
      writer: 'Suzanne M. Burns (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51u9u8uCSmL._SX388_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=19p8usbn3xeYa7n2fXoXzQd6PEqSE3p10'),
  Book(
      id: 342,
      subject: 'Management of Nursing Services and Education',
      title: 'Basic Clinical Nursing Skills',
      writer: 'EPHTI',
      edition: '',
      image:
          'https://reader009.staticloud.net/reader009/html5/20180705/5868dc191a28ab27408c2b1c/bg3.png',
      rating: 5.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1BEeCk6w4KfySf3rKTiymCciPahaIWplW'),
  Book(
      id: 343,
      subject: 'Medical Surgical Nursing',
      title:
          'All-in-One Nursing Care Planning Resource : Medical-Surgical, Pediatric, Maternity, and Psychiatric-Mental Health',
      writer: 'By (author)  Pamela L. Swearingen',
      edition: '3rd',
      image:
          'https://d1w7fb2mkkr3kw.cloudfront.net/assets/images/book/lrg/9780/3232/9780323262866.jpg',
      rating: 4.3,
      description:
          '''The only book with nursing care plans for all core clinical areas, All-In-One Care Planning Resource, 3rd Edition, provides 100 care plans with the nursing diagnoses and interventions you need to know to care for patients in all settings. It includes care plans for pediatric, maternity, and psychiatric nursing in addition to medical-surgical nursing, so you can use just one book throughout your entire nursing curriculum. A new online care plan tutorial walks you through the steps of creating care plans, and updates keep you current with the latest clinical developments, new pharmacologic treatments, QSEN patient safety standards, and evidence-based practice guidelines. Edited by Pamela Swearingen, this book is known for its clear, straightforward approach, its practical and consistent format, and its detailed rationales.



NANDA-I nursing diagnoses are incorporated throughout the text to keep you current with NANDA-I terminology and the latest diagnoses.
Color-coded sections for medical-surgical, maternity, pediatric, and psychiatric-mental health nursing care plans make it easier to find information quickly.
A consistent format for each care plan allows faster lookup of topics, with headings for Overview/Pathophysiology, Health Care Setting, Assessment, Diagnostic Tests, Nursing Diagnoses, Desired Outcomes, Interventions with Rationales, and Patient-Family Teaching and Discharge Planning.
Prioritized nursing diagnoses are listed in order of importance and physiologic patient needs. 
A two-column format for nursing assessments/interventions and rationales makes it easier to scan information.
Detailed rationales for each nursing intervention help you to apply concepts to specific patient situations in clinical practice.
Outcome criteria with specific timelines help you to set realistic goals for nursing outcomes and provide quality, cost-effective care.



NEW! Care plan for normal labor and birth addresses nursing care for the client experiencing normal labor and delivery.
UPDATED content is written by practicing clinicians and covers the latest clinical developments, new pharmacologic treatments, patient safety considerations, and evidence-based practice guidelines.
NEW full-color design makes the text more user friendly, and includes NEW color-coded tabs and improved cross-referencing and navigation aids for faster lookup of information.
NEW! Leaf icon highlights coverage of complementary and alternative therapies including information on over-the-counter herbal and other therapies and how these can interact with conventional medications.''',
      link:
          'https://drive.google.com/uc?export=download&id=1y5CC0xdgaB7e64FYemXsEnK-MW7RBJ2V'),
  Book(
      id: 344,
      subject: 'Medical Surgical Nursing',
      title:
          'Medical-Surgical Nursing: Assessment and Management of Clinical Problems',
      writer:
          'Sharon L. Lewis (Author), Shannon Ruff Dirksen  (Author), Margaret McLean Heitkemper (Author), Linda Bucher  (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51hm0G8lfyL._SX394_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=10_9fT5-LDCXjtctDp9z6iF7cOToRVrz7'),
  Book(
      id: 345,
      subject: 'Medical Surgical Nursing',
      title:
          'Brunner & Suddarth\'s Textbook of Medical-Surgical Nursing (Textbook of Medical-Surgical Nursing (Brunner & Sudarth)',
      writer:
          'Hinkle PhD RN CNRN, Janice L. (Author), Cheever PhD RN, Kerry H. (Author)',
      edition: '13th Edition vol 1 and 2',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41ZJCz8HbBL._SX385_BO1,204,203,200_.jpg',
      rating: 3.2,
      description:
          '''Prepare for medical-surgical nursing practice and success on the NCLEX with Brunner & Suddarth\'s Textbook of Medical-Surgical Nursing, 13th Edition . A favorite resource for students and practicing nurses for almost a half-century, this book provides comprehensive yet accessible coverage of a broad range of medical conditions while focusing on the nursing process and the nurse’s role in caring for and educating patients and families within today’s complex health care delivery system.
Up-to-date coverage of the health care needs of people with disabilities, nursing research findings, ethical considerations, and evidence-based practice gives you opportunities to refine your clinical decision-making skills. Fully updated and enhanced, this new edition provides a fully integrated solution that promotes clinical judgment, performance, and success on the NCLEX examination and in nursing practice.
Key Features in the 13th Edition:
NEW! Concept Mastery Alerts clarify difficult concepts, informed by data from Misconception Alert questions in PrepU for Brunner & Suddarth\'s Textbook of Medical-Surgical Nursing , 12e.
NEW! Quality and Safety Nursing Alerts build upon previous edition’s Nursing Alerts to highlight issues related to quality and safety nursing care.
NEW! The updated unit openers include new Case Studies with QSEN Competency Focus to highlight a competency and related knowledge, skills, and attitudes. Additional information for these case studies related to NANDA-I, NIC, NOC and the nursing process is available online.
NEW! Prioritization Questions have been added to the Critical Thinking Exercises .
UPDATED! Genetics Charts and Ethical Dilemma Charts have been revised to reflect the latest advances in the field.
UPDATED! Critical care information has been updated to further the authors\' goal to have the most up-to-date and clinically relevant content on critical care throughout the book.
EXPANDED! Expanded coverage of obesity, highlighted with a new icon, focuses on this epidemic health problem in our society.
STEAMLINED! The Table of Contents has been reorganized for a more logical sequence and flow.
REVISED! The accompanying Study Guide now features reorganized content and revised questions.
Nursing Process sections, Plans of Nursing Care , and Critical Care sections
More than 2,900 NCLEX-style review questions
Assessment Charts, Risk Factor Charts, Guidelines Charts , Genetics in Nursing Practice Charts, Patient Education Charts, Health Promotion Charts , Ethics and Related Issues Charts , and Pharmacology Charts and tables.
Gerontologic Considerations sections, Physiology/Pathophysiology figures, and Home Care Checklists
Nursing Research Profiles and EBP questions help students learn the importance of evidence-based practice.
Concepts in Action Animations bring anatomy, physiology and pathophysiology concepts to life .''',
      link:
          'http://93.174.95.29/main/2329000/c45f369e58247e95e3760d78e3964ed5/Brunner%2C%20Lillian%20Sholtis_%20Cheever%2C%20Kerry%20H._%20Hinkle%2C%20Janice%20L._%20Suddarth%2C%20Doris%20Smith%20-%20Brunner%20%26%20Suddarth%E2%80%99s%20textbook%20of%20medical-surgical%20nursing-Lippincott%20Williams%20%26%20Wilkins%20%282014%29.pdf'),
  Book(
      id: 346,
      subject: 'Medical Surgical Nursing',
      title: 'Medical-Surgical Nursing Demystified',
      writer: 'Jim Keogh (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51iM32Jx0BL._SX400_BO1,204,203,200_.jpg',
      rating: 4.0,
      description:
          '''The fun, fast, and effective way to master medical-surgical nursing and use your knowledge in real-world situations

If you\'re looking for an engaging, reader-acclaimed review that boils medical-surgical nursing down to its most essential, must-know points your search ends here! Medical-Surgical Nursing Demystified, Third Edition is a complete yet concise overview of the major body systems and the diseases and disorders that can affect them. You will learn about hallmark signs and symptoms, diagnostic tests, treatment, and nursing intervention, so you have the knowledge to help your patients as a student and as a nurse once you start your career.

Since Medical-Surgical Nursing can be challenging for a beginner, the book is written to provide an organized, outline approach to learning about major diseases, and the role the nurse can play in the treatment process. Studying is easy and effective with key objectives, important terms, brief overviews, tables and diagrams, and NCLEX®-style questions throughout the book. Medical-Surgical Nursing Demystified, Third Edition ends with a comprehensive final exam that covers all the content found in the book.''',
      link:
          'http://93.174.95.29/main/2342000/43b9ceb9218e96bae17511b24cc32925/Mary%20Digiulio_%20Jim%20Keogh%20-%20Medical-Surgical%20Nursing%20Demystified-McGraw-Hill%20Education%20_%20Medical%20%282018%29.epub'),
  Book(
      id: 347,
      subject: 'Medical Surgical Nursing',
      title:
          'Focus on Adult Health: Medical-Surgical Nursing (Pellico Medical-Surgical)',
      writer: 'Linda Honan Pellico (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41LvYyr-HwL._SX383_BO1,204,203,200_.jpg',
      rating: 3.8,
      description:
          '''Focus on Adult Health: Medical-Surgical Nursing, is uniquely designed to prepare today’s students to succeed as practicing nurses by focusing on the most important medical disorders and key nursing responsibilities.
“As the demand for nurses continues to grow, new nurses are entering a dynamic and challenging work environment, and many feel unprepared,” said Linda H. Pellico, RN, PhD, the lead author and editor of the textbook. “We developed this textbook and related tools to prepare students for the reality of medical-surgical nursing. We need to teach students how to think like a nurse, and how to focus quickly on the most critical aspects. Beyond taking care of what you see, nursing is about predicting and preventing risks, so this book details risk factors, clinical presentation, and treatment.”
The textbook prepares students for both the NCLEX exam and for daily nursing practice by focusing on the need-to-know content. Both the text and the supporting tools include features designed to reinforce student understanding, such as:

· Focused Assessment Guides, which summarize key content for quick reference and review,

· Guidelines for Nursing Care: Clear, step-by-step “how to” procedures are paired with action rationales to explain why actions are important,

· Innovative Art Program: Connects text-based concepts with real-life patient scenarios,

· Nursing alerts, evidence-based practice boxes, and risk factor boxes, to keep students engaged and increase their comprehension.''',
      link:
          'http://93.174.95.29/main/2375000/d14856cd9355a6fca326bc32007a26c0/Linda%20Honan%20-%20Focus%20on%20Adult%20Health_%20Medical-Surgical%20Nursing-LWW%20%282018%29.pdf'),
  Book(
      id: 348,
      subject: 'Medical Surgical Nursing',
      title:
          'Medical-Surgical Nursing: Critical Thinking for Person-Centred Care',
      writer:
          'Tracey Levett-Jones (Author), Priscilla Lemone (Author), Karen Burke (Author), Gerene Bauldoff (Author), Paula Gubrud-Howe (Author), & 1 more',
      edition: '3rd',
      image: 'https://images-fe.ssl-images-amazon.com/images/I/617IL7KCLDL.jpg',
      rating: 4.5,
      description:
          '''The third Australian edition of Medical–Surgical Nursing: Critical Thinking for Person-Centred Care will help prepare you for your nursing journey. It will challenge you to excel and support you as you learn.

Students will be provided with a strong knowledge base, an understanding of contemporary practice issues in Australia and the capacity for sound clinical reasoning. These professional attributes will allow you to provide nursing care that is safe and effective. This easily understood, straightforward Australian edition integrates the following concepts: epidemiology, pathophysiology, pharmacology, legal and ethical issues, therapeutic communication, interprofessional communication and cultural competence.

This textbooks has been designed to:

emphasise a person-centred philosophy whereby the person who is the recipient of care is seen as an integral member of the team and consideration of their needs and wishes is paramount
foster critical thinking and clinical reasoning skills as the basis for nursing excellence in clinical practice
recognise the nurse’s role as an essential member of the interprofessional healthcare team.''',
      link:
          'http://93.174.95.29/main/2373000/43f8bc01298c570c3fd012b49e425d5d/Levett-Jones%2C%20Tracey_%20Lemone%2C%20Priscilla_%20Burke%2C%20Karen%20-%20Medical-Surgical%20Nursing_%20Critical%20Thinking%20for%20Person-Centred%20Care.%201-3-Pearson%20%282017%29.pdf'),
  Book(
      id: 349,
      subject: 'Medical Surgical Nursing',
      title:
          'Medical-Surgical Nursing: Concepts for Interprofessional Collaborative Care, Single Volume',
      writer: 'Donna D. Ignatavicius; M. Linda Workman; Cherie Rebar',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51RLHGH12pL._SX389_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''Awarded second place in the 2018 AJN Book of the Year Awards in Medical-Surgical Nursing!

Healthcare is evolving at an incredible pace and with it, the roles and responsibilities of the medical-surgical nurse. Ensure you are fully equipped to thrive and adapt in this ever-changing nursing environment with Ignatavicius, Workman, and Rebar\'s Medical-Surgical Nursing: Concepts for Interprofessional Collaborative Care, 9th Edition. This trendsetting text not only covers all essential adult health knowledge, but also reinforces the application, conceptual thinking, and clinical judgment skills that today’s nurses need to stay one step ahead in delivering exceptional patient care, no matter the environment. As with previous "Iggy" editions, you’ll find a unique collaborative care approach to adult health nursing, a thorough integration of QSEN competencies, extensive NCLEX® Exam preparation, and a direct, reader-friendly tone throughout the text. This ninth edition incorporates two emerging and complementary trends ― the Core Competencies for Interprofessional Collaborative Practice and a more conceptual approach teaching and learning ― areas that will ground you in how to think like a nurse and how to apply the knowledge you gain from the text to clinical practice. There are a lot of med-surg nursing texts out there, but there’s only one that combines all the information, concepts, and on-the-job realities in a way that makes perfect sense: "Iggy!"

Trendsetting QSEN integration emphasizes patient safety and evidence-based practice with Nursing Safety Priority boxes, including Drug Alerts, Critical Rescues, and Action Alerts.
UNIQUE! Emphasis on clinical judgment helps you develop skills in clinical reasoning and clinical decision-making when applying concepts to clinical situations.
Strong emphasis on NCLEX Exam preparation includes chapter-opening Learning Outcomes and chapter-ending Get Ready for the NCLEX Examination! sections organized by NCLEX Client Needs Categories, plus NCLEX Examination Challenge questions, with an answer key in the back of the book and on the Evolve companion website.
Exceptionally readable content features shorter sentences, straightforward vocabulary, and a direct, reader-friendly writing style.
NEW! Enhanced emphasis on conceptual teaching and learning features a strong integration of nursing concepts and exemplars throughout the book via new concept overview chapters, chapter-opening concept lists, and a focus on concept exemplars within disorders chapters.
NEW! Integration of interprofessional collaborative practice takes the book’s hallmark collaborative management approach to the next level via new collaboration-focused Clinical Judgment Challenges, integration of a new Teamwork & Interprofessional Collaboration concept, and in-depth integration within TEACH lesson plans.
NEW! Deeper integration of Tanner’s model of clinical nursing judgment utilizes Tanner’s terminology within nursing process headings, NCLEX Examination Challenge questions, and Key Points.
NEW! Stronger emphasis on health promotion and community-based care includes revised and updated content throughout the text to reflect the reality that most adult health care no longer takes place as long-term stays in high-acuity settings.
NEW! More consistent, interprofessional terminology for patient problems promotes interprofessional collaboration through the promotion of a common healthcare language.
NEW! Updated content throughout reflects the most recent changes in practice and the latest evidence-based guidelines, particularly national and international treatment guidelines and protocols.
NEW! More consistent learning outcomes now incorporate QSEN and nursing concepts in a more consistent and intentional manner from chapter to chapter.''',
      link:
          'http://93.174.95.29/main/2376000/e32dd6348e80b1cd165d306da52aefac/Donna%20D.%20Ignatavicius_%20M.%20Linda%20Workman_%20Cherie%20Rebar%20-%20Medical-Surgical%20Nursing_%20Concepts%20for%20Interprofessional%20Collaborative%20Care%2C%20Single%20Volume-Saunders%20%282017%29.pdf'),
  Book(
      id: 350,
      subject: 'Medical Surgical Nursing',
      title:
          'Study Guide for Medical-Surgical Nursing: Assessment and Management of Clinical Problems (Study Guide for Medical-Surgical Nursing: Assessment & Management of Clinical Problem)',
      writer:
          'Lewis RN PhD FAAN, Sharon L. (Author), Bucher RN PhD CEN CNE, Linda (Author), Dirksen RN PhD, Shannon Ruff (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51RMwVngOQL._SX389_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''Prepare for success in the classroom! Corresponding to the chapters in the 9th edition of Lewis\' market-leading Medical-Surgical Nursing, this study guide offers a complete review of content and a wide range of activities to help you understand key nursing concepts. Alternate item format questions reflect the most current NCLEX test plan. To make studying easier, answers for all exercises are included in the back of the book.

A wide variety of clinically relevant exercises and activities includes NCLEX examination-style multiple-choice questions, prioritization and delegation questions, case studies, fill-in-the-blank questions, anatomy and physiology review, critical thinking activities, and more.
Answers to all questions are included in the back of the book, giving you immediate feedback as you study.
Additional alternate item format questions incorporating prioritization and delegation are included to better prepare you for the most current NCLEX exam.
Attractive two-color design ties the study guide to the textbook.''',
      link:
          'http://93.174.95.29/main/1156000/31a467b7a02912d33f76ec28861743ca/%28Study%20Guide%20for%20Medical-Surgical%20Nursing_%20Assessment%20%26%20Management%20of%20Clinical%20Problem%29%20Sharon%20L.%20Lewis%20RN%20%20PhD%20%20FAAN%2C%20Shannon%20Ruff%20Dirksen%20RN%20%20PhD%2C%20Linda%20Bucher%20RN%20%20PhD%20%20CEN%20-%20Study%20Guide%20for%20Medical.pdf'),
  Book(
      id: 351,
      subject: 'Medical Surgical Nursing',
      title: 'Oxford handbook of surgical nursing',
      writer:
          'Alison Smith (Editor), Maria Kisiel (Editor), Mark Radford (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41ERj4m%2BhwL._SX276_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''Concise, practical, and packed full of clinical information, the Oxford Handbook of Surgical Nursing is the essential resource for all those working in nursing practice surgery and its sub-specialties. Easily-accessible, this handbook provides all of the information and practical advice needed to care effectively and professionally for surgical patients.

This handbook provides a thorough introduction to the principles and practice of the care of patients undergoing the range of surgical procedures. It covers all of the core elements of surgical care from point of diagnosis, through to discharge and rehabilitation. The Oxford Handbook of Surgical Nursing provides clinical knowledge and skills for managing complex cases in the hospital or clinic. This guide will assist the reader in understanding the core role of the surgical nurse within the modern surgical team, to plan, implement and evaluate patient care delivery, and to manage complications arising from surgery. Evidence-based, and following the latest national guidelines, you can be sure this will be an indispensable companion, for all nurses, whether new to the specialty, or more experienced in surgical care.''',
      link:
          'http://93.174.95.29/main/1704000/103789f862df577f8e91c4a96475e05f/%28Oxford%20handbooks%20in%20nursing._%20Oxford%20medical%20publications%29%20Kisiel%2C%20Maria_%20Radford%2C%20Mark_%20Smith%2C%20Alison%20-%20Oxford%20handbook%20of%20surgical%20nursing-Oxford%20University%20Press%20%282016%29.pdf'),
  Book(
      id: 352,
      subject: 'Medical Surgical Nursing',
      title:
          'Lippincott\'s Review for Medical-Surgical Nursing Certification (LWW, Springhouse Review for Medical-Surgical Nursing Certification)',
      writer: 'Lippincott (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Y2wUWx4wL._SX398_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''Lippincott\'s Review for Medical-Surgical Nursing Certification, Fifth Edition provides the information nurses need to achieve certification in the specialty of medical-surgical nursing. This helpful reference covers the broad range of content found on the actual examinations, including disorders by body system, such as coronary artery disease, COPD, and diabetes. The product reviews signs and symptoms, diagnostic tests, medical treatments, nursing assessments, and interventions for scores of health problems. Concise refreshers on wound care, perioperative nursing, collaborative practice, nursing research, and legal issues are also included. Review questions after each chapter and an end-of-book posttest help assess the nurse\'s preparedness for the exam. The book is appropriate for exams of both major certifying bodies: the ANCC and the AMSN.''',
      link:
          'http://93.174.95.29/main/897000/28e10bd0f1a4fd128e107fd49682f39f/M.%20Pottage%20-%20Lippincott%27s%20review%20for%20medical-surgical%20nursing%20certification-Wolters%20Kluwer%20Health_Lippincott%20Williams%20%26%20Wilkins%20%20%282012%29.pdf'),
  Book(
      id: 353,
      subject: 'Medical Surgical Nursing',
      title: 'Medical-Surgical Nursing: Patient-Centered Collaborative Care',
      writer:
          'Ignatavicius MS RN CNE ANEF, Donna D. (Author), Workman PhD RN FAAN, M. Linda (Author)',
      edition: '7th (2 volume)',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51vPsn9pPoL._SX393_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''Using a uniquely collaborative and reader-friendly approach, expert authors Donna D. Ignatavicius and M. Linda Workman cover all the latest trends, evidence-based treatment guidelines, and additional updated information needed for safe clinical practice in medical-surgical nursing. This seventh edition features an expanded emphasis on patient safety and NCLEX Examination preparation, new ties to the QSEN priorities for patient safety, and a greater alignment with the language and focus of clinical practice. A new chapter on evidence-based practice and a wealth of effective online learning tools help solidify your mastery of medical-surgical nursing.

UNIQUE! Collaborative approach presents all medical, surgical, nursing, and other interventions through the lens of the nursing process.
Reader-friendly, direct writing style makes this one of the most readable medical-surgical nursing textbooks available.
UNIQUE! Cutting-edge focus on the latest trends in nursing practice and nursing education prepares you for both today and tomorrow\'s nursing practice.
UNIQUE! Integrated tools for NCLEX preparation get you ready for your licensure examination.
Chapter-opening Learning Outcomes are linked to Self-Assessment Questions for the NCLEX Examination on the Evolve website.
Unique chapter-ending Get Ready for the NCLEX Examination! sections include Key Points organized by NCLEX Client Needs Categories.
UNIQUE! Focus on nursing concepts helps bridge the gap between the concepts learned in Nursing Fundamentals, and disorders content learned in the medical-surgical nursing course.
UNIQUE! Emphasis on clinical decision-making teaches you to apply concepts to true-to-life clinical situations.
UNIQUE! Concentration on the core body of knowledge for the RN level of medical-surgical nursing practice focuses your attention on \'need-to-know\' content to pass the NCLEX Examination and practice safely as a beginning nurse.
Rich array of effective learning aids includes:
Best Practice for Patient Safety & Quality Care
Best Practice for Emergency Care
Patient and Family Education: Preparing for Self-Management 
Nursing Focus on the Older Adult
Home Care Assessment
Focused Assessment
Common Examples of Drug Therapy
Evidence-Based Practice
Concept Maps
Laboratory Profiles
Assessment Using Gordon\'s Functional Health Patterns
Patient safety is emphasized throughout with Nursing Safety Priority features, including Drug Alerts, Critical Rescue, and Action Alerts.
More NCLEX Examination preparation, including integrated NCLEX Examination Challenges to prepare you for the types of questions you will see on todayÕs NCLEX Examination.
Greater use of realistic clinical language familiarizes you with the terminology actually used by nurses, physicians, and other healthcare professionals in clinical practice today.
Streamlined, prioritized coverage of the nursing process highlights the most important patient problems, regardless of whether they can be addressed by independent nursing actions or must be addressed by collaborative interventions.
UNIQUE! New ties to QSEN competencies for patient safety inform you of the best safety practices in medical-surgical nursing.
More coverage of evidence-based practice teaches you how to appraise the validity of research and provides synopses of recent nursing research and other evidence-based articles.
Student Resources on Evolve include animations, video clips, audio clips, tutorials, Review Questions for the NCLEX Examination, and more.
Improved layout and design streamlines content for an easier reading experience.
Coverage of core genetics competencies acquaints you with new research demonstrating a genetic component to many diseases and disorders.
Increased emphasis on health promotion and promotion of self-care offers strategies for helping people recover from illness and stay well and prevent illness.
All-new Concept Maps match the streamlined nursing process format of the text and employ more creative, visually oriented symbols.''',
      link:
          'http://93.174.95.29/main/1113000/1f0aa1e7a6a7179efae9e8c4717ca719/Donna%20D.%20Ignatavicius%20MS%20%20RN%20%20ANEF%2C%20M.%20Linda%20Workman%20PhD%20%20RN%20%20FAAN%20-%20Medical-Surgical%20Nursing_%20Patient-Centered%20Collaborative%20Care%2C%20Single%20Volume%2C%207e-Saunders%20%282012%29.epub'),
  Book(
      id: 354,
      subject: 'Medical Surgical Nursing',
      title:
          'Springhouse Review for Medical-Surgical Nursing Certification (Springhouse Nursing Review Series)',
      writer: 'Springhouse  (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51L4r4xZ3aL._SX398_BO1,204,203,200_.jpg',
      rating: 4.4,
      description: '''''',
      link:
          'http://93.174.95.29/main/1489000/887b9729388ac356cf9bfce33978ed67/%28Springhouse%20Nursing%20Review%20Series%29%20Springhouse%20-%20Springhouse%20Review%20for%20Medical-Surgical%20Nursing%20Certification-Wolters%20Kluwer%20Health%20%282006%29.pdf'),
  Book(
      id: 355,
      subject: 'Medical Surgical Nursing',
      title:
          'Winningham\'s Critical Thinking Cases in Nursing: Medical-Surgical, Pediatric, Maternity, and Psychiatric',
      writer:
          'Mariann M. Harding MSN RN CNE (Author), Julie S. Snyder  (Author), Barbara A. Preusser PhD FNPc (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51yq3%2B7StiL._SX389_BO1,204,203,200_.jpg',
      rating: 3.4,
      description:
          '''Develop your critical thinking and clinical reasoning skills with 150 realistic case studies from the four major clinical practice areas: medical-surgical, pediatric, maternity, and psychiatric/mental health nursing. Each case covers a common problem, drawn from actual clinical experiences and written by nurses who are clinical experts. All cases have been thoroughly updated and revised to reflect current clinical practices, with integrated content on pharmacology, nutrition, and diagnostic/laboratory tests to encourage you to think critically about all aspects of care. This fifth edition also features an increased emphasis on patient management, and new documentation and communication exercises. Plus new NCLEX® Examination format-questions help you prepare for success on the NCLEX® Examination and provide safe, quality patient care.

Three-part organization presents cases in three parts: 1) Medical-Surgical Cases; 2) Pediatric, Maternity, and Psychiatric Cases; and 3) Other/Advanced Cases, the latter covering key topics such as multi-system disorders and emergency situations.
Realistic case study approach incorporates cases drawn from actual clinical experiences to help you identify changes, anticipate possible complications, and initiate therapeutic interventions.
Increasing case complexity provides you with a foundation on which to build as you advance to more difficult cases.
Two new pediatric case studies strengthen your ability to recognize and effectively manage common disorders presenting in pediatric patients.
New NCLEX Examination-format questions have been added throughout, including multiple choice, prioritization/ordering, chart/exhibit, and dosage calculation questions.
Increased number of higher-level questions requires clinical reasoning rather than simply memorizing and recalling information.
An emphasis on patient management reinforces the type of clinical decision-making needed in the clinical setting as well as reflecting the type of questions on the latest NCLEX Examination.
Over 25 new illustrations and graphics such as ECG strips, lab/diagnostic test reports, anatomical diagrams, and medication labels are now interwoven throughout the book.
New documentation and communication exercises ask you to document relevant patient information or to use the "SBAR" communication technique to communicate patient findings to the physician.''',
      link:
          'http://93.174.95.29/main/1167000/724c2bad2cb7c87776ca8163967154de/Mariann%20M.%20Harding%20MSN%20RN%20CNE%2C%20Julie%20S.%20Snyder%2C%20Barbara%20A.%20Preusser%20PhD%20%20FNPc%20-%20Winningham%27s%20Critical%20Thinking%20Cases%20in%20Nursing_%20Medical-Surgical%2C%20Pediatric%2C%20Maternity%2C%20and%20Psychiatric%2C%205e-Mosby%20%282012.pdf'),
  Book(
      id: 356,
      subject: 'Midwifery and Obstetrical Nursing',
      title: 'Obstetric and Gynecological Nursing',
      writer: 'EPHTI',
      edition: '',
      image:
          'https://reader009.staticloud.net/reader009/html5/20180705/5868dc191a28ab27408c2b1c/bg3.png',
      rating: 5.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1AEKSYK07u6FdRe7qRSZkxulwJsTh5qZE'),
  Book(
      id: 357,
      subject: 'Midwifery and Obstetrical Nursing',
      title:
          'All-in-One Nursing Care Planning Resource : Medical-Surgical, Pediatric, Maternity, and Psychiatric-Mental Health',
      writer: 'By (author)  Pamela L. Swearingen',
      edition: '3rd',
      image:
          'https://d1w7fb2mkkr3kw.cloudfront.net/assets/images/book/lrg/9780/3232/9780323262866.jpg',
      rating: 4.3,
      description:
          '''The only book with nursing care plans for all core clinical areas, All-In-One Care Planning Resource, 3rd Edition, provides 100 care plans with the nursing diagnoses and interventions you need to know to care for patients in all settings. It includes care plans for pediatric, maternity, and psychiatric nursing in addition to medical-surgical nursing, so you can use just one book throughout your entire nursing curriculum. A new online care plan tutorial walks you through the steps of creating care plans, and updates keep you current with the latest clinical developments, new pharmacologic treatments, QSEN patient safety standards, and evidence-based practice guidelines. Edited by Pamela Swearingen, this book is known for its clear, straightforward approach, its practical and consistent format, and its detailed rationales.



NANDA-I nursing diagnoses are incorporated throughout the text to keep you current with NANDA-I terminology and the latest diagnoses.
Color-coded sections for medical-surgical, maternity, pediatric, and psychiatric-mental health nursing care plans make it easier to find information quickly.
A consistent format for each care plan allows faster lookup of topics, with headings for Overview/Pathophysiology, Health Care Setting, Assessment, Diagnostic Tests, Nursing Diagnoses, Desired Outcomes, Interventions with Rationales, and Patient-Family Teaching and Discharge Planning.
Prioritized nursing diagnoses are listed in order of importance and physiologic patient needs. 
A two-column format for nursing assessments/interventions and rationales makes it easier to scan information.
Detailed rationales for each nursing intervention help you to apply concepts to specific patient situations in clinical practice.
Outcome criteria with specific timelines help you to set realistic goals for nursing outcomes and provide quality, cost-effective care.



NEW! Care plan for normal labor and birth addresses nursing care for the client experiencing normal labor and delivery.
UPDATED content is written by practicing clinicians and covers the latest clinical developments, new pharmacologic treatments, patient safety considerations, and evidence-based practice guidelines.
NEW full-color design makes the text more user friendly, and includes NEW color-coded tabs and improved cross-referencing and navigation aids for faster lookup of information.
NEW! Leaf icon highlights coverage of complementary and alternative therapies including information on over-the-counter herbal and other therapies and how these can interact with conventional medications.''',
      link:
          'https://drive.google.com/uc?export=download&id=1y5CC0xdgaB7e64FYemXsEnK-MW7RBJ2V'),
  Book(
      id: 358,
      subject: 'Nursing Foundation',
      title: 'Kozier & Erb\'s Fundamentals of Nursing',
      writer:
          'Audrey T. Berman (Author), Shirlee Snyder (Author), Geralyn Frandsen EdD MSN RN (Author)',
      edition: '10th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Q0i1PqsxL._SX392_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Help each student think like a nurse using a clear, consistent approach 
Consistency and accessibility are essential to student success in the Fundamentals of Nursing course. With its clear, approachable, writing style, Kozier & Erb’s Fundamentals of Nursing sets the foundation for nursing excellence. Coverage of the key concepts of contemporary nursing, as well as the latest nursing evidence, standards, and competencies, helps prepare readers to become effective nurses. To help students develop their clinical-reasoning abilities, new QSEN features draw connections to actual nursing practice. All basic and fundamental skills for the registered nurse are described within the nursing process. Students will learn to think like nurses as they see how the material they are reading is applied in nursing practice.

Also available with MyNursingLab® 
This title is also available with MyNursingLab—an online homework, tutorial, and assessment program designed to engage students in the Fundamentals of Nursing course and improve results. Its guided learning path is proven to help students think like a nurse as they move beyond memorization to true understanding through application.

NOTE: You are purchasing a standalone product; MyNursingLab does not come packaged with this content. If you would like to purchase both the physical text and MyNursingLab, search the Pearson website.

MyNursingLab should only be purchased when required by an instructor. Students, if interested in purchasing this title with MyNursingLab, ask your instructor for the correct package ISBN and Course ID. Instructors, contact your Pearson representative for more information.''',
      link:
          'https://drive.google.com/uc?export=download&id=1tTNJSAJ3qkXIHbPuxaD6lQSJwU4P1skG'),
  Book(
      id: 359,
      subject: 'Nursing Foundation',
      title: 'Foundations of Basic Nursing',
      writer:
          'Lois White , By (author)  Gena Duncan , By (author)  Wendy Baumle',
      edition: '3rd',
      image:
          'https://d1w7fb2mkkr3kw.cloudfront.net/assets/images/book/lrg/9781/1113/9781111320942.jpg',
      rating: 4.7,
      description:
          '''This fully updated second edition of Foundations of Basic Nursing lays the foundation of introductory material for your nursing course of study. The book focuses on foundation concepts you will need to know, such as holistic care, legal responsibilities, communication, and client teaching, while also helping you master skills needed to be an effective and caring nurse. The special features throughout the book are specially designed to emphasize specific information, such as: Life Cycle Considerations, Client Teaching, Infection Control, Safety, Community/Home Health Care, Cultural Considerations, and Professional Tips. Critical Thinking Questions are included throughout the book to encourage the user to apply the chapter\'s content. At the end of each chapter, readers will find a Summary and Review Questions, along with References/Suggested Readings and Resources.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Ml8sygwz-KwbZ2X1qatkvh45J6zhL9ji'),
  Book(
      id: 360,
      subject: 'Nursing Foundation',
      title: '[(Fundamental Nursing Skills)]',
      writer: 'Author: Penelope Ann Hilton',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/31Frvl1E2rL._SX264_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=168NtI0lBaXwPdPMFELlBy6yCv5ylgDmW'),
  Book(
      id: 361,
      subject: 'Nutrition',
      title: 'Nutrition: A Handbook for Nurses',
      writer: 'Carolyn Best (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41j8gle0ALL._SX331_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''This book provides a comprehensive look at all aspects of nutrition from roles and responsibilities to caring for a patient with specific nutritional needs. It is aimed primarily at nurses and addresses some of the issues they will encounter when caring for patients nutritional needs in a hospital setting. It also highlights the benefits of a hospital based Nutrition Team providing a multidisciplinary approach to nutrition. It includes a number of case studies to clarify some of the issues discussed and concludes by examining issues that need to be considered before discharging a patient home from hospital into the community.''',
      link:
          'https://drive.google.com/uc?export=download&id=171KQ0G4iiXHbafS__iqAPFzdV-vV0TAl'),
  Book(
      id: 362,
      subject: 'Nutrition',
      title: 'Nutrition Education for the Health Care Professions',
      writer:
          'Guest Editors: Martin Kohlmeier, Caryl A. Nowson, Rose Ann DiMaria-Ghalili,',
      edition: '',
      image: '',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1swGmY93KP0f0aCFLANOItZ5dQQ_JrVGF'),
  Book(
      id: 363,
      subject: 'Psychology',
      title:
          'APA Style Simplified Writing in Psychology, Education, Nursing, and Sociology',
      writer: 'Bernard C. Beins (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41TRhVykRJL._SX331_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''This is a compact but comprehensive guide to writing clearly and effectively in APA style.

Demonstrates how to write objective scientific research papers using interesting prose
Incorporates guidelines from the 6th edition of the APA publication manual
Explores how to develop ideas, connect them to what others have written, and express them clearly
Discusses the differences between written, oral, and poster presentations and offers instructions for applying APA style to each''',
      link:
          'https://drive.google.com/uc?export=download&id=1VWmgBzvawzYeOrGDg47gHbPGfIcDH7r4'),
  Book(
      id: 364,
      subject: 'Psychology',
      title:
          'All-in-One Nursing Care Planning Resource : Medical-Surgical, Pediatric, Maternity, and Psychiatric-Mental Health',
      writer: 'By (author)  Pamela L. Swearingen',
      edition: '3rd',
      image:
          'https://d1w7fb2mkkr3kw.cloudfront.net/assets/images/book/lrg/9780/3232/9780323262866.jpg',
      rating: 4.3,
      description:
          '''The only book with nursing care plans for all core clinical areas, All-In-One Care Planning Resource, 3rd Edition, provides 100 care plans with the nursing diagnoses and interventions you need to know to care for patients in all settings. It includes care plans for pediatric, maternity, and psychiatric nursing in addition to medical-surgical nursing, so you can use just one book throughout your entire nursing curriculum. A new online care plan tutorial walks you through the steps of creating care plans, and updates keep you current with the latest clinical developments, new pharmacologic treatments, QSEN patient safety standards, and evidence-based practice guidelines. Edited by Pamela Swearingen, this book is known for its clear, straightforward approach, its practical and consistent format, and its detailed rationales.



NANDA-I nursing diagnoses are incorporated throughout the text to keep you current with NANDA-I terminology and the latest diagnoses.
Color-coded sections for medical-surgical, maternity, pediatric, and psychiatric-mental health nursing care plans make it easier to find information quickly.
A consistent format for each care plan allows faster lookup of topics, with headings for Overview/Pathophysiology, Health Care Setting, Assessment, Diagnostic Tests, Nursing Diagnoses, Desired Outcomes, Interventions with Rationales, and Patient-Family Teaching and Discharge Planning.
Prioritized nursing diagnoses are listed in order of importance and physiologic patient needs. 
A two-column format for nursing assessments/interventions and rationales makes it easier to scan information.
Detailed rationales for each nursing intervention help you to apply concepts to specific patient situations in clinical practice.
Outcome criteria with specific timelines help you to set realistic goals for nursing outcomes and provide quality, cost-effective care.



NEW! Care plan for normal labor and birth addresses nursing care for the client experiencing normal labor and delivery.
UPDATED content is written by practicing clinicians and covers the latest clinical developments, new pharmacologic treatments, patient safety considerations, and evidence-based practice guidelines.
NEW full-color design makes the text more user friendly, and includes NEW color-coded tabs and improved cross-referencing and navigation aids for faster lookup of information.
NEW! Leaf icon highlights coverage of complementary and alternative therapies including information on over-the-counter herbal and other therapies and how these can interact with conventional medications.''',
      link:
          'https://drive.google.com/uc?export=download&id=15hZTc9iBiqMddAWe-_ifd01TIEVqW9AJ'),
  Book(
      id: 365,
      subject: 'Psychology',
      title: 'A Guide to Mental Health and Psychiatric Nursing',
      writer: 'R. Sreevani (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51uiT0L41aL._SX356_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1OuQMdOuhAFNvBYI8SrpJ-LXquqRxF8NQ'),
  Book(
      id: 366,
      subject: 'Psychology',
      title:
          'Nursing Diagnoses in Psychiatric Nursing: Care Plans and Psychotropic Medications (Townsend, Nursing Diagnoses in Psychiatric Nursing)',
      writer: 'Mary C. Townsend DSN PMHCNS-BC (Author)',
      edition: '8th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/5191PT7NtML._SX281_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Here s the 20th Anniversary Edition of the most complete and easy-to-use resource on how to develop practical, individualized plans of care for psychiatric and mental health patients. It s really 2 books in 1! The first half provides the diagnostic information needed to create a care plan; the second half covers the safe administration of psychotropic medications. And, the concepts can be applied to a variety of healthcare settings from in-patient hospitalization through the outpatient clinic to home health and private practice. Completely revised and updated throughout, the 8th Edition reflects all of the new knowledge and new medications in the field, including an expanded section on psychotropic medications that encompasses all of today s new drugs and the 2009-2011 content in the NANDA Nursing Diagnoses: Taxonomy II.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Ln2xKSM4jSqVjGDpnBVuIwzTJd6o6Z4k'),
  Book(
      id: 367,
      subject: 'Sociology',
      title:
          'APA Style Simplified Writing in Psychology, Education, Nursing, and Sociology',
      writer: 'Bernard C. Beins (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41TRhVykRJL._SX331_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''This is a compact but comprehensive guide to writing clearly and effectively in APA style.

Demonstrates how to write objective scientific research papers using interesting prose
Incorporates guidelines from the 6th edition of the APA publication manual
Explores how to develop ideas, connect them to what others have written, and express them clearly
Discusses the differences between written, oral, and poster presentations and offers instructions for applying APA style to each''',
      link:
          'https://drive.google.com/uc?export=download&id=1VWmgBzvawzYeOrGDg47gHbPGfIcDH7r4'),
  Book(
      id: 368,
      subject: 'Nursing Pharmacology',
      title: 'Saunders Nursing Drug Handbook',
      writer: 'Robert J. Kizior BS RPh (Author), Keith Hodgson (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51f3m-ibJoL._SX298_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''With essential information on more than 1,000 generic and 4,000 trade name drugs, Saunders Nursing Drug Handbook 2019 is the go-to guide for students and nurses alike. The 2019 edition is organized alphabetically by generic drug name for quick and easy access and includes over 270 updates to Black Box Alerts. This user-friendly format also includes comprehensive coverage of IV drug administration, nursing considerations, and fixed combinations. To promote better patient care, it uniquely guides you through clinical priorities in the practice setting and is organized alphabetically by generic drug name for quick reference. Plus, new drug monographs cover approximately 33 newly approved drugs by the FDA; and thoroughly updated monographs include new interactions, precautions, and alerts.

Over 1,000 generic name drugs (encompassing over 4,000 trade name drugs) are organized alphabetically with A to 2Z tabs to make accessing important information quick and easy.
Detailed information for each drug distinguishes side effects and adverse reactions to help you identify which are most likely to occur.
Special text treatment for high-alert drugs that pose the greatest risk for patient harm, as well as an appendix for drug names that sound alike and look alike, help promote safe drug administration.
UNIQUE! Frequently-used herb monographs and herb interactions keep you informed of the effects of commonly encountered herbs.
Classifications section features an overview of actions and uses for drug families.
Top 100 Drugs list helps you easily identify the most frequently administered drugs.
Nursing implications are organized in a functional nursing process framework and include headings for Baseline Assessment, Intervention/Evaluation, and Patient/Family Teaching.
Information on lifespan and disorder-related dosage variations equips you with special considerations for pediatric, geriatric, hepatic, and immune- or renal-compromised patients.
Extensively expanded IV content features a heading for IV compatibilities and expanded rates of infusion, reconstitutions, drip rates, test doses, flushing, and incompatibilities.
Fixed combinations are included in dosages of each combined drug directly within the individual monographs to help you understand different drug dose options for specific diseases.
Cross-references to the 400 top U.S. brand-name drugs are located directly in the main section of the book for easier accessibility.
Customizable and printable monographs for 100 of the most commonly used drugs and quarterly drug updates are located on the free Evolve companion site.
Therapeutic and toxic blood level information shows you the patient implications for drug administration.
Comprehensive IV Compatibility Chart foldout arms you with compatibility information for 65 intravenous drugs.
Newly approved drugs are listed in the front of the book for quick and easy access to this timely information.
A sample drug monograph with callouts helps you understand how to use the book more efficiently.
NEW! Drug monographs for approximately 33 newly approved drugs by the FDA equip you with the most current drug information.
NEW! Thoroughly updated monographs throughout feature updated information on new interactions, precautions, alerts, patient teaching instructions, and other need-to-know information.
NEW and UPDATED! Over 270 Black Box Alerts updates and additions highlight the drugs found to carry a significant risk of serious or even life-threatening adverse effects.''',
      link:
          'https://drive.google.com/uc?export=download&id=18Dd9Nkt_ipkb4ZygRX5FIit5Qb20aocM'),
  Book(
      id: 369,
      subject: 'Anesthesia',
      title: 'Morgan & Mikhail\'s Clinical Anesthesiology',
      writer:
          'John F. Butterworth (Author), David C. Mackey  (Author), John D. Wasnick (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41XFDgN4PkL._SX397_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''The most user-friendly, clinically relevant overview of the practice of anesthesiology

A Doody\'s Core Title for 2017!

Current, concise, and engagingly written, Morgan & Mikhail’s Clinical Anesthesiology, Fifth Edition is a true essential for all anesthesia students and practitioners. This trusted classic delivers comprehensive coverage of the field’s must-know basic science and clinical topics in a clear, easy-to-understand presentation. Indispensable for coursework, exam review, and as a clinical refresher, this trusted text has been extensively updated to reflect the latest research and developments.

Here’s why Clinical Anesthesiology is the best anesthesiology resource:

NEW full-color presentation
NEW chapters on the most pertinent topics in anesthesiology, including anesthesia outside of the operating room and a revamped peripheral nerve blocks chapter that details ultrasound-guided regional anesthesia
Up-to-date discussion of all relevant areas within anesthesiology, including equipment, pharmacology, regional anesthesia, pathophysiology, pain management, and critical care
Case discussions promote application of the concepts to real-world practice
Numerous tables and figures encapsulate important information and facilitate memorization''',
      link:
          'https://drive.google.com/uc?export=download&id=1Cw8uFW90pZZp2h01cv8Cmhs-LcC_4hkL'),
  Book(
      id: 370,
      subject: 'Anesthesia',
      title: 'Anaesthesia at a Glance',
      writer: 'Julian Stone  (Author), William Fawcett  (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/415PoBA-SEL._SX385_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1N2Ps9Hqz8uRTzr4JFrWEs1DtOJ5-tMV4'),
  Book(
      id: 371,
      subject: 'Anesthesia',
      title: 'General anesthesia',
      writer: '',
      edition: '',
      image:
          'https://upload.wikimedia.org/wikipedia/en/f/f9/No-image-available.jpg',
      rating: 0.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1f716_Gb31fAoPJFxcbV7n_3KMDL9YsyY'),
  Book(
      id: 372,
      subject: 'Anesthesia',
      title: 'ANESTHESIA EQUIPMENTS',
      writer: '',
      edition: '',
      image:
          'https://upload.wikimedia.org/wikipedia/en/f/f9/No-image-available.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1xh0y-piy15cZbCWxvAm8kKeNwePD7AT9'),
  Book(
      id: 373,
      subject: 'Anesthesia',
      title: 'Anesthesia Emergencies',
      writer: 'Keith J. Ruskin (Editor), Stanley H. Rosenbaum (Editor)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/4131gHEzzrL._SX284_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Anesthesia Emergencies contains relevant step-by-step information on how to detect, manage, and treat complications and emergencies during the perioperative period. Concisely written, highlighted sections on immediate management and risk factors reinforce essential points for easy memorization, while consistent organization and checklists provide ease of learning and clarity. Anesthesia providers will find this book an indispensable resource, describing assessment and treatment of life-threatening situations, including airway, thoracic, surgical, pediatric, and cardiovascular emergencies. The second edition contains a revised table of contents which presents topics in order of their priority during emergencies, as well as two new chapters on crisis resource management and disaster medicine.''',
      link:
          'https://drive.google.com/uc?export=download&id=1P3snZDjL9FFy4CUBiKixc95ApJzsXA_i'),
  Book(
      id: 374,
      subject: 'Anesthesia',
      title:
          'Hadzic\'s Textbook of Regional Anesthesia and Acute Pain Management',
      writer: 'by Admir Hadzic  (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/514NlQsGKfL._SX393_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''The ultimate text on the principles and practice of regional anesthesia and pain management – thoroughly updated

A Doody’s Core Title for 2019! 

Since its first edition, Hadzic’s Textbook of Regional Anesthesia and Acute Pain Management has been the standard reference for students and practitioners of anesthesiology. Presented in full color, this classic covers the theory and practice of regional anesthesia in its entirety, providing readers with both the physiologic principles and specific, state-of-the-art patient-management protocols and techniques.

This second edition has been completely updated to reflect the profound advances in the field.  These developments include the use of ultrasonography for imaging of peripheral nerves and the central nervous system, advances in the up-to-date understanding of the role of regional anesthesia in preventing postoperative pain, and the use of point-of-care ultrasound for a vast number of other perioperative applications. The second edition features some of the most detailed and didactic anatomical artwork to date. Being a world-wide reference text, this edition also includes anatomical landmark-based and nerve stimulator guided peripheral nerve blocks.

● More than 200 expert contributors and collaborators

● Evidence-based information that spans the entire field of RAPM
● Full-color clinical images and functional anatomy illustrations – nearly all new to this edition
● Easy-to-follow clinical decision-making diagrams, flow charts, practical tables, and clinical pearls
● Up-to-date information on the etiology, prevention, and management of a wide range of complications
● Detailed chapters on pediatric regional anesthesia
● In-depth discussion of region-specific ultrasound te''',
      link:
          'https://drive.google.com/uc?export=download&id=1kJpeYVM4gNz7SBnUNvdowX1fXFHrxwXI'),
  Book(
      id: 375,
      subject: 'Anesthesia',
      title: 'Essentials of Trauma Anesthesia',
      writer: 'Albert J. Varon (Editor), Charles E. Smith (Editor)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Pv56zF-qL._SX331_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Covering the most important topics in trauma anesthesia, this updated edition provides anesthesiology trainees and practitioners with a practical basis for managing trauma patients. Many recent advances in trauma care are identified, including paradigm shifts in the management of bleeding and coagulopathy, new neuromuscular blockade and anticoagulant reversal drugs, and updated clinical practice guidelines. This volume provides a concise, practical review of the essential elements in the care of the severely injured trauma patient, including emergency airway management, fluid and blood resuscitation, monitoring, coagulation therapy, regional and general anesthesia, and perioperative care. Edited by two of the most experienced trauma anesthesiologists in the United States, with chapters written by experts from leading US and Canadian trauma centers with the highest and most varied caseload of critically injured patients, Essentials of Trauma Anesthesia identifies new trends in surgery and anesthesiology practices that impact on the management of trauma patients.''',
      link:
          'https://drive.google.com/uc?export=download&id=1i-fpgKUh690EOIisltmKOzDEFaJ9LUEj'),
  Book(
      id: 376,
      subject: 'Anesthesia',
      title: 'Clinical Cases in Anesthesia',
      writer:
          'Reed MD, Allan P. (Author), Yudkowitz MD FAAP, Francine S. (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Wor-BUQML._SX384_BO1,204,203,200_.jpg',
      rating: 3.6,
      description:
          '''Prepare for the oral boards with the thoroughly updated Clinical Cases in Anesthesia. This comprehensive and current anesthesia review tool presents case studies representing today\'s most commonly encountered clinical situations, equipping you to master the latest anesthesia treatment protocols and practice guidelines and achieve your very best score.

Learn the most practical solutions to contemporary problems, and understand the relevant scientific and clinical principles, through actual case studies presented in a helpful Q&A format.
Study on the go! Browse the complete contents online at www.expertconsult.com!
Review the most recent knowledge with updated coverage of the cardiovascular, respiratory, and central nervous system; updated abdomen, trauma, and post-anesthesia care sections; and a completely new section on critical care.
Stay abreast of the latest treatment options, practice guidelines, and pharmacology information with comprehensive updates throughout.''',
      link:
          'https://drive.google.com/uc?export=download&id=1VYB893Hg7Ut0ze4MiIM5wYBRrsF5zd5O'),
  Book(
      id: 377,
      subject: 'Anesthesia',
      title: 'Anesthesia Equipment: Principles and Applications',
      writer:
          'by Ehrenwerth MD, Jan (Author), Eisenkraft MD MRCP(UK) FFARCS, James B. (Author), Berry MD, James M (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41nIHswwKyL._SX396_BO1,204,203,200_.jpg',
      rating: 5.0,
      description:
          '''Anesthesia Equipment: Principles and Applications, 2nd Edition, by Dr. Jan Ehrenwerth and Dr. James B. Eisenkraft, offers expert, highly visual, practical guidance on the full range of delivery systems and technology used in practice today. It equips you with the objective, informed answers you need to ensure optimal patient safety.

"This is a comprehensive, up-to-date reference textbook covering all aspects of physics and equipment for the modern American anaesthetist. It may be helpful to those studying for American fellowship examinations but is not suited to preparation for the UK FRCA examinations." Reviewed by: I.Wrench on behalf of the British Journal of Anaesthesia, Feb 2014 

Make informed decisions by expanding your understanding of the physical principles of equipment, the rationale for its use, delivery systems for inhalational anesthesia, systems monitoring, hazards and safety features, maintenance and quality assurance, special situations/equipment for non-routine adult anesthesia, and future directions for the field.
Ensure patient safety with detailed advice on risk management and medicolegal implications of equipment use.
Apply the most complete and up-to-date information available on machines, vaporizers, ventilators, breathing systems, vigilance, ergonomics, and simulation.
Visualize the safe and effective use of equipment thanks to hundreds of full-color line drawings and photographs.
Access the complete text and images online, fully searchable, at www.expertconsult.com.''',
      link:
          'http://93.174.95.29/main/1405000/2755529709e12d24bb1c1e4769a9916b/J.%20Ehrenwerth%2C%20J.%20B.%20Eisenkraft%2C%20J.%20M.%20Berry%20-%20Anesthesia%20Equipment_%20Principles%20and%20Applications-Saunders%20%282013%29.pdf'),
  Book(
      id: 378,
      subject: 'Anesthesia',
      title: 'Duke\'s Anesthesia Secrets',
      writer: 'Duke MD MBA, James (Author), Keech MD FAAP, Brian M. (Editor)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/517WzpVk1aL._SX306_BO1,204,203,200_.jpg',
      rating: 4.6,
      description:
          '''Get quick answers to the most important clinical questions with Duke’s Anesthesia Secrets, 5th Edition! Authors James Duke, MD and Brian M. Keech, MD present this easy-to-read, bestselling resource that uses the popular and trusted Secrets Series® Q&A format. It provides rapid access to the practical, "in-the-trenches" know-how you need to succeed – both in practice and on board and recertification exams.

Zero in on key information with bulleted lists, tables, mnemonics, illustrations, practical tips from the authors, and "Key Points" boxes that provide a concise overview of important board-relevant content.
Review essential material efficiently with the "Top 100 Secrets in Anesthesiology" – perfect for last-minute study or self-assessment.
Get the evidence-based guidance you need to provide optimal care for your patients – ideal for medical students, residents, fellows, and practitioners.
Apply all the latest advances in techniques, technology, and pharmacology, and explore effective solutions to a full range of clinical issues in anesthesiology.
Expert Consult eBook version included with purchase. This enhanced eBook experience allows you to search all of the text, figures, and tables from the book on a variety of devices.''',
      link:
          'http://93.174.95.29/main/1405000/5ae66ff4332c4d59037b79814bca84f1/James%20Duke%2C%20Brian%20Keech%20-%20Duke%27s%20Anesthesia%20Secrets-Saunders%20%282015%29.pdf'),
  Book(
      id: 379,
      subject: 'Anesthesia',
      title:
          'Essential Clinical Anesthesia Review: Keywords, Questions and Answers for the Boards',
      writer: 'Linda S. Aglio (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51QT2fmKP5L._SX385_BO1,204,203,200_.jpg',
      rating: 4.5,
      description:
          '''This concise, evidence-based board review book, organized according to the ABA keyword list, covers all the fundamental concepts needed to pass written and re-certification board examinations. Each chapter begins with a case scenario or clinical problems from everyday practice, followed by concise discussion and clinical review questions and answers. Discussion progresses logically from preoperative assessment and intraoperative management to postoperative pain management, enhancing the reader\'s knowledge and honing diagnostic and clinical management skills. New guidelines and recently developed standards of care are also covered.''',
      link:
          'https://drive.google.com/uc?export=download&id=1IMQeYJN-BjzcVfqSszNGbKG0fXb12d2s'),
  Book(
      id: 380,
      subject: 'Anesthesia',
      title: 'Basics of Anesthesia',
      writer: 'Pardo MD, Manuel (Author), Miller MD MS, Ronald D. (Author)',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41POCSJqeIL._SX398_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''The undisputed leading text in its market, Basics of Anesthesia, 7th Edition, provides comprehensive coverage of both basic science and clinical topics in anesthesiology. Drs. Manuel C. Pardo, Jr. and Ronald D. Miller, in conjunction with many new contributors, have ensured that all chapters are thoroughly up to date and reflect the latest advances in today’s practice. Unparalleled authorship, concise text, easy-to-read chapters, and a user-friendly format make this text the #1 primer on the scope and practice of anesthesiology.

Presents the combined expertise of two of the most prolific and renowned anesthesia experts worldwide, along with more than 80 expert contributing authors.
Uses a concise, at-a-glance format to cover both the basic science and essential clinical aspects of the field, including pathophysiology, pharmacology, regional anesthesia, anesthetic management, and special problems and patient groups.
Features high-quality images that offer a detailed visual understanding of regional anesthesiology and much more.
Includes new topics and chapters on Neurotoxicity of Anesthesia, Palliative Care, Sleep Medicine, Perioperative Surgical Home, Trauma, and Natural/Human-Induced Disasters.
Expert Consult™ eBook version included with purchase. This enhanced eBook experience allows you to search all of the text, figures, and references from the book on a variety of devices.''',
      link:
          'http://93.174.95.29/main/2097000/a29af91401c2744fa44b10a9671d013e/Manuel%20Pardo%2C%20Ronald%20D.%20Miller%20-%20Basics%20of%20Anesthesia-Elsevier%20%282017%29.pdf'),
  Book(
      id: 381,
      subject: 'Anesthesia',
      title: 'Handbook of Clinical Anesthesia',
      writer:
          'Author(s): Paul G. Barash , Bruce F. Cullen MD, Robert K. Stoelting MD, Michael K. Cahalan MD, M. Christine Stock MD, Rafael Ortega MD',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41TIj8hmmvL._SX296_BO1,204,203,200_.jpg',
      rating: 3.8,
      description:
          '''The Handbook of Clinical Anesthesia, Seventh Edition , closely parallels Clinical Anesthesia, Seventh Edition , and presents the essential information found in the larger text in a concise, portable format. Extensive changes made to the parent textbook are reflected in the Handbook ; chapters have been completely updated and a new chapter covering anesthesia for laparoscopic and robotic surgeries has been added.
The Handbook makes liberal use of tables and graphics to enhance rapid access to information. This comprehensive, pocket-sized reference guides you through virtually every aspect of perioperative, intraoperative, and postoperative patient care.
Inside You’ll Find…\'
Step-by-step procedures to administer anesthesia for cardiac surgery, obstetric surgery, minimally invasive procedures, chronic pain management, and more
ASA guidelines for patient care and safety included
Robust appendices include formulas, Atlas of Electrocardiography, Pacemaker and ICD Protocols, American Heart Association resuscitation protocols, ASA Standards and Guidelines, difficult airway algorithms, malignant hyperthermia protocol, and herbal medications
A clear, consistent writing style that makes critical material easy to locate and comprehend
NEW to the Seventh Edition …\'
A new chapter covering Anesthesia for Laparoscopic and Robotic Surgeries has been added
Two new appendices – Atlas of Electrocardiography and Pacemaker and Implantable Cardiac Defibrillator Protocols''',
      link:
          'https://drive.google.com/uc?export=download&id=1ER0M6o1TmsMuSEFu6J9PWOYZrWufr3WE'),
  Book(
      id: 382,
      subject: 'Anesthesia',
      title: 'Clinical Anesthesia',
      writer: 'Paul G. Barash (Author)',
      edition: '8th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51vHJY89vUL._SX422_BO1,204,203,200_.jpg',
      rating: 3.5,
      description:
          '''Where experts turn for definitive answers! Clinical Anesthesia covers the full spectrum of clinical issues and options in anesthesiology, providing insightful coverage of pharmacology, physiology, co-existing diseases, and surgical procedures. Unmatched in its clarity and depth of coverage as well as its robust multimedia features, this classic clinical reference brings you the very latest essential knowledge in the field, equipping you to effectively apply today’s standards of care and make optimal clinical decisions on behalf of your patients.''',
      link:
          'https://drive.google.com/uc?export=download&id=1bKDpsUvSvXEucj2E12MA4rUqqlY7RX0m'),
  Book(
      id: 383,
      subject: 'Anesthesia',
      title: 'Miller\'s Anesthesia, 2-Volume Set',
      writer:
          'Miller MD MS, Ronald D. (Author), Eriksson MD PhD FRCA, Lars I. (Author), Fleisher MD FACC, Lee A (Author)',
      edition: '8th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51wdYbrjtML._SX423_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''From fundamental principles to advanced subspecialty procedures, Miller’s Anesthesia covers the full scope of contemporary anesthesia practice. This go-to medical reference book offers masterful guidance on the technical, scientific, and clinical challenges you face each day, in addition to providing the most up-to-date information available for effective board preparation.

"Miller’s Anesthesia continues to serve as the most in-depth review textbook of contemporary anesthesia". Reviewed by: Genevieve Lalonde on behalf of Canadian Journal of Anesthesia  Date: Jan 2015

Address the unique needs of pediatric patients with guidance from an entire section on pediatric anesthesia.
View more than 1,500 full-color illustrations for enhanced visual clarity.
Access step-by-step instructions for patient management, as well as an in-depth analysis of ancillary responsibilities and problems.
Quickly reference important concepts with ‘Key Points’ boxes integrated into every chapter.
Stay current on today\'s most recent anesthetic drugs and guidelines/protocols for anesthetic practice and patient safety, and access expanded coverage on new techniques such as TEE and other monitoring procedures.
Remain at the forefront of new developments in anesthesia with coverage of hot topics including Non-OR Anesthesia; Role of the Anesthesiologist in Disasters; Sleep Medicine in Anesthesia; Perioperative and Anesthesia-related Neurotoxicity; Anesthetic Implications of Complementary and Alternative Medicine; and Robotics.
Study brand-new chapters on Perioperative Fluid Management; Extracorporeal Support Therapies; Anesthesia for Organ Donation/Procurement; and Malignant Hyperthermia and other Genetic Disorders.
Expert Consult eBook version included with purchase. This enhanced eBook experience allows you to conveniently search the full text, references, tables, and index from the book on your favorite devices, in addition to accessing regular updates, related websites, and an expanded collection of procedural videos.
Your purchase entitles you to access the web site until the next edition is published, or until the current edition is no longer offered for sale by Elsevier, whichever occurs first. If the next edition is published less than one year after your purchase, you will be entitled to online access for one year from your date of purchase. Elsevier reserves the right to offer a suitable replacement product (such as a downloadable or CD-ROM-based electronic version) should access to the web site be discontinued.''',
      link:
          'http://93.174.95.29/main/1405000/bf931c2f1ddd234eb8d7425847f0abec/Ronald%20D.%20Miller%20%28ed.%29%20-%20Miller%27s%20Anesthesia%2C%202-Volume%20Set-Saunders%20%282014%29.pdf'),
  Book(
      id: 384,
      subject: 'Anesthesia',
      title: 'Principles and Practice of Pediatric Anesthesia',
      writer: 'H Snehalata Dhayagude (Author), Nandini M Dave (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51tgQnWjlfL._SX370_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''This book provides a detailed overview of techniques in paediatric anaesthesia. Beginning with the basic principles of child anatomy, growth and development, the following section explains general principles of anaesthetising a child, from preoperative evaluation and induction, to monitoring, pain assessment, ventilation strategies, and transfusion therapy. The book covers anaesthesia for numerous sub-specialties including neonatal surgery, ENT procedures, dentistry, liver disease, thoracic surgery, ophthalmic procedures, and much more. The final sections describe special circumstances and complications, and associated topics such as safety and quality, and ethical issues. Comprehensive appendices provide an index of syndromes and anaesthetic implications, a paediatric drug index, quick reference tables and formulae, and a photo gallery. Key points Presents overview of techniques in paediatric anaesthesia Covers numerous sub-specialties, special circumstances and complications Discusses associated topics including safety and quality, and ethical issues Comprehensive appendices provide indexes of syndromes, anaesthetic implications and drug dosages, as well as quick reference tables and a photo gallery''',
      link:
          'https://drive.google.com/uc?export=download&id=1ju3QuD2IFN4nnX3eoGqmiv1v0Nbc9nmd'),
  Book(
      id: 385,
      subject: 'Anesthesia',
      title: 'Handbook of Local Anesthesia',
      writer: 'Malamed DDS, Stanley F. (Author)',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/31cvz01nkVL._SX351_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''Learn to prevent, recognize, and manage complications of local anesthesia administration. Written by Dr. Stanley Malamed, the leading expert on anesthesia in dentistry, the Handbook of Local Anesthesia, 7th Edition covers all the latest advances in science, instrumentation, and pain control techniques. From basic concepts to specific injection techniques, from dosage charts to the proper care and handling of equipment, this how-to guide provides in-depth, full-color coverage of key anesthesia topics, including specific hazards and errors in technique that may result in complications. Recognized as THE local anesthesia textbook in dentistry for over 30 years, the seventh edition has been thoroughly updated with the latest in safe anesthesia practices in dentistry.

Written by Dr. Stanley Malamed, one of the most in-demand and globally recognized experts on dental anesthesia and sedation.
Full-color photographs and line drawings enhance important points throughout book.
Step-by-step procedures cover the techniques for administering intraoral anesthesia. 
Detailed descriptions of routes of anesthesia administration included throughout text. 
Logical Organization of content divides book into four parts including –Drugs, The Armamentarium, Techniques of Regional Anesthesia in Dentistry, and Complications, Legal Considerations, Questions, and the Future
NEW! Updated and enhanced content throughout reflects latest research evidence.
NEW! Two added chapters cover problems in achieving pain control and their solutions; and recent advances in local anesthesia. 
NEW! Addition of an Expert Consult Site allows you to search the entire book electronically.''',
      link:
          'https://drive.google.com/uc?export=download&id=1AwhLTfiGQOGT2Y_vhT0PjwbVcHzmGp5A'),
  Book(
      id: 386,
      subject: 'Anesthesia',
      title: 'Basic Physiology for Anaesthetists',
      writer:
          'David Chambers  (Author), Christopher Huang (Author), Gareth Matthews  (Author)',
      edition: '1st edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51xFBonktBL._SX382_BO1,204,203,200_.jpg',
      rating: 0.9,
      description:
          '''Every trainee in anaesthesia requires a thorough understanding of basic physiology and its application to clinical practice. This comprehensively illustrated textbook bridges the gap between medical school and reference scientific texts. It covers the physiology requirements of the Primary FRCA examination syllabus. Chapters are organised by organ system, with particular emphasis given to the respiratory, cardiovascular and nervous systems. The practical question-and-answer format helps the reader prepare for the oral examination, while \'clinical relevance\' boxes translate the physiological concepts to clinical practice. The authors include two medical physiologists and a Specialty Registrar in anaesthesia, and thereby bring a unique blend of expertise. This ensures that the book is up-to-date, accessible, and pitched appropriately for the trainee anaesthetist. Packed with easily understood, up-to-date and clinically relevant material, this convenient volume provides an essential \'one-stop\' resource in physiology for junior anaesthetists.''',
      link:
          'https://drive.google.com/uc?export=download&id=13Gw5XZn1pQ4SZJRb0Zt_8N5VFQd8l2KT'),
  Book(
      id: 387,
      subject: 'Anesthesia',
      title: 'Drugs in Anaesthesia and Intensive Care',
      writer: 'Edward Scarth (Author), Susan Smith (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41qZfXkkG7L._SX265_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''An essential reference text, the fifth edition of this popular book details drugs in anaesthesia and intensive care in an A-Z format. The book describes the pharmacokinetics and pharmacodynamics of all the drugs commonly used by anaesthetists. The A-Z organisation allows rapid access to specific information on the properties and characteristics of almost 200 drugs.

The new edition includes a complete revision of all the featured drugs, and the addition of key new drugs. New diagrams of particular drug structures and comparison tables aid comparison of differences within a drug class for exam revision. Improved navigation in the index enables prompt discoverability of information.

Written in a concise, bullet-point style to allow quick access to information, the book contains all necessary drug references for anaesthetists in training, consultant anaesthetists, intensive care nurses, and anaesthetic assistants.''',
      link:
          'https://drive.google.com/uc?export=download&id=1vsG54peNg5Cnw-Bjij27anTTY7DD0IR3'),
  Book(
      id: 388,
      subject: 'Anesthesia',
      title: 'Anesthesiology',
      writer:
          'David E. Longnecker (Author), Mark F. Newman (Author), Warren M. Zapol (Author), Warren Sandberg (Author), Sean Mackey (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51vmfH78hjL._SX393_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''The gold-standard text in anesthesiology – from the field’s brightest, most respected minds

Written by an internationally known team of experts, Anesthesiology, Third Edition provides a 360-degree view of the field, covering all the anesthetic considerations from preoperative preparation through postoperative care, and the full breadth of anesthesia practice, including pain medicine and critical care medicine.  Presented in full color and updated to capture the latest breakthroughs and advances,  Anesthesiology  is designed to provide the practitioner with an authoritative single-source reference that spans the full spectrum of anesthesia practice.

Much more than a how-to manual of anesthetic techniques, Anesthesiology, Third Edition presents an accessible compilation of concepts and principles that affirms its status as the cornerstone text in anesthesiology. This edition emphasizes important trends in both the specialty and healthcare in general. These trends include team-based anesthesia care, the remarkable growth of pain medicine practice, and the expanded need for clinicians who are skilled in the practice of critical care medicine.

Features:

• Four new pain medicine chapters, plus an expanded section on anesthetic considerations and perioperative management of co-existing disease
• Key Points and Key References encapsulate must-know information and guide you to important articles for further research
• Balanced presentations present clinical information, practical clinical procedures, and the molecular and scientific foundations of anesthesia practice
• Essential for residents and students preparing for initial certification, and for practitioners preparing for recertification''',
      link:
          'https://drive.google.com/uc?export=download&id=1voyI-OTQzo8a3-3X1UXVitAS6ReLoqh1'),
  Book(
      id: 389,
      subject: 'Anesthesia',
      title: 'Anesthesia in Day Care Surgery',
      writer:
          'M.M. Begani (Editor), Dheeraj V. Mulchandani (Editor), Shagufta choudhary (Editor)',
      edition: '1st Edition',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/31yLa65%2BJ5L._SX321_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''This book features a collection of guidelines for anesthesia in day care surgery, covering all medical specialties that may look to venture into the ambulatory surgery domain. It provides various practical tips that can be used in day-to-day practice by anesthetists and surgeons alike, and covers various anesthetic protocols used by the stalwarts of the industry to illustrate the ideal techniques for anesthesia in day care surgery.''',
      link:
          'https://drive.google.com/uc?export=download&id=1vrjK9JVEVZT7-UewPnaJ5r_A7SgYgkoW'),
  Book(
      id: 390,
      subject: 'Anesthesia',
      title:
          'Gupta and Gelb\'s Essentials of Neuroanesthesia and Neurointensive Care',
      writer:
          'Arun Gupta (Editor), Adrian Gelb (Editor), Derek Duane  (Editor), Ram Adapa (Editor)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51o5t5fZhJL._SX331_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''This updated second edition of Gupta and Gelb\'s Essentials of Neuroanesthesia and Neurointensive Care contains the ideal combination of updated information for the practitioner, presented in easy-to-digest short chapters. With an essential clinical focus on key neuroanesthesia and neurointensive care knowledge, it is a practical guide for any practitioner of neuroanesthesia, beginner, occasional or experienced. The user-friendly format contains bullet points to ensure retention of important data, key points to summarize the take-home messages, suitable images to enhance understanding, and pertinent and appropriate references to allow for further exploration of the topics. This book is ideal for residents and others undergoing neuroanesthesia training. It is also a great tool for Operating Room nurses and other OR support workers, neurosurgical residents and neurointensive care professionals. This will also be a useful book to supplement knowledge for postgraduate fellowship and Board examinations.''',
      link:
          'https://drive.google.com/uc?export=download&id=1HuZAq4D1yfQhYg-mXbsFiL4CgYdUVwob'),
  Book(
      id: 391,
      subject: 'Emergency',
      title: 'Anesthesia Emergencies',
      writer: 'Keith J. Ruskin (Editor), Stanley H. Rosenbaum (Editor)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/4131gHEzzrL._SX284_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Anesthesia Emergencies contains relevant step-by-step information on how to detect, manage, and treat complications and emergencies during the perioperative period. Concisely written, highlighted sections on immediate management and risk factors reinforce essential points for easy memorization, while consistent organization and checklists provide ease of learning and clarity. Anesthesia providers will find this book an indispensable resource, describing assessment and treatment of life-threatening situations, including airway, thoracic, surgical, pediatric, and cardiovascular emergencies. The second edition contains a revised table of contents which presents topics in order of their priority during emergencies, as well as two new chapters on crisis resource management and disaster medicine.''',
      link:
          'https://drive.google.com/uc?export=download&id=1P3snZDjL9FFy4CUBiKixc95ApJzsXA_i'),
  Book(
      id: 392,
      subject: 'Emergency',
      title: 'CURRENT Diagnosis and Treatment Emergency Medicine',
      writer: 'C. Keith Stone (Author), Roger L. Humphries (Author)',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/516-1hw%2B4yL._SX397_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''An instant-access guide to the diagnosis, treatment, and management of the conditions most likely to present in the emergency department

A Doody’s Core Title for 2019! 

Essential for anyone practicing in an emergency department or acute care setting, this new edition of CURRENT Diagnosis & Treatment Emergency Medicine strikes the perfect balance between brevity and clinical necessity.  It delivers exactly the amount of information needed for quick diagnosis, effective treatment, and improved outcomes – no more, no less.  Every chapter of this edition has been updated to reflect the latest breakthroughs and developments, and the book is filled with high-quality illustrations designed to clarify difficult concepts.

FEATURES:
• Strikes the perfect balance between brevity and clinical necessity, delivering exactly the amount of information needed for quick diagnosis, effective treatment, and improved outcomes  
• Emphasizes the immediate management of life-threatening problems, then covers the evaluation and treatment of specific disorders
• Priority-based and problem-oriented organization encompasses all aspects of emergency medicine, including common emergencies, trauma, and neonatal and pediatric emergencies
• Extensive at-a-glance algorithms facilitate rapid decision making
• Comprehensive tables of drugs commonly used in the ED''',
      link:
          'https://drive.google.com/uc?export=download&id=1G4JFXd9sqTP6ou_kB-uA6M0r3GKHoXRu'),
  Book(
      id: 393,
      subject: 'Emergency',
      title: 'Emergency Psychiatry (Cambridge Medicine (Hardcover))',
      writer:
          'Arjun Chanmugam (Editor), Patrick Triplett  (Editor), Gabor Kelen (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51MCy6HgEvL._SX329_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Many healthcare providers based in primary care, emergency care or other acute care environments encounter patients with psychiatric problems. These presentations can be difficult to manage and often pose significant challenges. A better understanding of most common psychiatric problems can greatly aid both providers and patients. Emergency Psychiatry reviews a wide range of common psychiatric disorders and provides succinct management guidelines. Written by emergency physicians and psychiatrists, Emergency Psychiatry is a rapid reference for the acute management of psychiatric disorders for all care providers, including, but not limited to, emergency physicians, internists, psychiatrists, social workers, family practitioners and other primary care providers.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Aj-3kOlT6abvo7LFAiCYdFdNpOfzZ78k'),
  Book(
      id: 394,
      subject: 'Emergency',
      title:
          'Pocket Emergency Paediatric Care: A Practical Guide to the Diagnosis and Management of Pedeatric Emergencies in Hospitals and Other Healthcare Facilities',
      writer:
          'Shafique Ahmad  (Author), David Southall (Author), Child Advocacy International (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41hPPhfCGCL._SX257_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''A pocket sized book containing the information needed immediately when confronted with a critically ill or injured neonate, baby or child. Contains, in a well presented format, all of the information relevant to clinical management within the first 1-2 hours after presentation. Is not dependent on high technology inputs and therefore most information within the pocket book is applicable anywhere in the world. There is also an emphasis, in addition to preventing mortality and morbidity, on the relief of suffering. There is thus a section on pain control. The book is laid out in a way that ensures easy access in an emergency. The sale of this book in rich countries will help support its distribution at low cost in poorly resourced countries.''',
      link:
          'https://drive.google.com/uc?export=download&id=1GMp2iz_EOcZoZrRHULU5MOMVIpzwxkjX'),
  Book(
      id: 395,
      subject: 'Emergency',
      title: 'Oxford Handbook of Emergency Medicine (Oxford Medical Handbooks)',
      writer:
          'Jonathan P. Wyatt  (Author), Robin N. Illingworth (Author), Colin A. Graham (Author), Kerstin Hogg (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41ECzPAWEFL._SX274_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Fully revised and updated, the Oxford Handbook of Emergency Medicine is the definitive, best-selling guide for all of the common conditions that present to the emergency department. Whether you work in emergency medicine, or just want to be prepared, this book will be your essential guide.

Following the latest clinical guidelines and evidence, written and reviewed by experts, this handbook will ensure you are up-to-date and have the confidence to deal with all emergency presentations, practices, and procedures. Following the latest developments in the field, such as infection control, DNR orders, advanced directives and learning disability. The book also includes new sections specifically outlining patient advice and information, as well as new and revised vital information on paediatrics and psychiatry. For all junior doctors, specialist nurses, paramedics, clinical students, GPs and other allied health professionals, this rapid-reference handbook will become a vital companion for both study and practice.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Zv_0yOhlnpyTZV_ZrBo7G9o6Bkg5nhIS'),
  Book(
      id: 396,
      subject: 'Psychiatry',
      title:
          'ICD-10 : The ICD-10 Classification of Mental and Behavioural Disorders : Clinical Descriptions and Diagnostic Guidelines',
      writer: '',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51RLGrmXWAL._SX320_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1SZnYAlds7EBSCbIc_-liLFMJMkVRUmFh'),
  Book(
      id: 397,
      subject: 'Psychiatry',
      title: 'Oxford Handbook of Psychiatry (Oxford Handbooks)',
      writer: 'Semple, David, Smyth, Roger',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41sgykhki6L._SX290_BO1,204,203,200_.jpg',
      rating: 4.3,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=16aurY0AlWlmYN0CqvbYKogZuNauHtiBr'),
  Book(
      id: 398,
      subject: 'Psychiatry',
      title: 'Psychiatry at a Glance',
      writer: 'Cornelius Katona (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41PRV2IAlvL._SX394_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1SZnYAlds7EBSCbIc_-liLFMJMkVRUmFh'),
  Book(
      id: 399,
      subject: 'Psychiatry',
      title: 'Psychiatry: Clinical Cases Uncovered (CaseBased)',
      writer: 'Peter Byrne (Author), Nicola Byrne (Author)',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41ygFKdd9ZL._SX382_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1Jsz5nCzMo0HFAsb6TQTA_4iZjTKebCpb'),
  Book(
      id: 400,
      subject: 'Psychiatry',
      title: 'Rapid Psychiatry',
      writer: 'Clare Oakley  (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41HkjGMj3tL._SX322_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1oEONU5iWKvK_9FeT5KEnLH3d0b2W48o2'),
  Book(
      id: 401,
      subject: 'Paediatric Dentistry',
      title: 'Paediatric Dentistry',
      writer: 'Welbury R.R. (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51i19-buBvL._SX309_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1HEkCDhkwQGM3zWF2dJ59K4Ezaq-3fgTo'),
  Book(
      id: 402,
      subject: 'Paediatric Dentistry',
      title: 'INTRODUCTION TO PEDIATRIC DENTISTRY',
      writer: '',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/515MevoYesL._SX331_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1RNMWVxHYb16d1oMnZw7rQF-olMWEW4ZH'),
  Book(
      id: 403,
      subject: 'Paediatric Dentistry',
      title: 'A Manual of Paediatric Dentistry',
      writer: 'Irwin M. Freedberg (Editor), Thomas B. Fitzpatrick (Editor)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51FE6500QHL._SX367_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1uFAiRm4t0JweHOlkeC97PMnmBuBtjNLV'),
  Book(
      id: 404,
      subject: 'Paediatric Dentistry',
      title: 'Paediatric Dentistry',
      writer:
          'Richard Welbury (Editor), Monty S. Duggal (Editor), Marie Thérèse Hosey (Editor)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/513QdrS5tLL._SX394_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''This new edition of Paediatric Dentistry is a trustworthy guide to the essentials of paediatric dentistry for both students and practitioners alike. 
 Written in a user-friendly style, this textbook contains over 18 fully up-to-date and comprehensive chapters. All content has been carefully structured to ensure the reader is provided with both key theoretical and practical information on paediatric dental care. Chapter content ranges from dental trauma and child safeguarding through to prevention and restorative treatments, in addition to further content on oral surgery and paediatric oral medicine. Each chapter is complemented by the use of key point boxes, full colour illustrations, and photographs to enhance the understanding clinical technique. With recommended further reading and extensive key references, this core text also encourages students to critically analyse and evaluate evidence. 
 Edited by a team of experts in the field, this is an excellent introduction to the field of paediatric dentistry for both undergraduate and post-graduate students as well as a key source of reference for practising clinicians.''',
      link:
          'https://drive.google.com/uc?export=download&id=1Va2D6eW_41cUhDzuoGMO2uB2FhimFKAX'),
  Book(
      id: 405,
      subject: 'Paediatric Dentistry',
      title: 'Paediatric Dentistry at a Glance (At a Glance (Dentistry))',
      writer:
          'Monty Duggal (Author), Angus Cameron (Author), Jack Toumba (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41vy5jAhGgL._SX395_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Paediatric Dentistry at a Glance is the new title in the highly popular at a Glance series. It provides a concise and accessible introduction and revision aid, comprehensively covering all the constituent sub-topics that comprise paediatric dentistry. Following the familiar, easy-to-use at a Glance format, each topic is presented as a double-page spread with facts accompanied by clear diagrams and clinical photographs encapsulating essential knowledge. Structured over 7 sections, Paediatric Dentistry at a Glance covers: * Physical assessment and treatment planning * Prevention and management of dental caries * Traumatic Injuries * Management of children with special health care needs * Paediatric oral medicine and Pathology * Dental and oro-facial anomalies Paediatric Dentistry at a Glance draws together clinical and scientific elements to provide a comprehensive review of comprehensive oral health care for infants and children though adolescence. It is an ideal companion for all students of dentistry, junior clinicians and members of the dental team with an interest in paediatric dentistry.''',
      link:
          'https://drive.google.com/uc?export=download&id=1961HxIw9zr-pagLXVkyaUWgmV3quSTYC'),
  Book(
      id: 406,
      subject: 'Prosthodontics',
      title: 'Fundamentals of Fixed Prosthodontics',
      writer:
          'Sumiya Hobo (Author), Lowell D. Whitsett (Author), Richard Jacobi (Author), Susan E. Brackett (Author), Herbert T. Shillingburg (Author, Editor)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51hmhiYJMuL._SX361_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1A9qn_MgYofip2a7lQ1e493IB2QyHlwtw'),
  Book(
      id: 407,
      subject: 'Prosthodontics',
      title: 'Stewart\'s Clinical Removable Partial Prosthodontics',
      writer: 'Rodney D. Phoenix, David R. Cagna, Charles F. DeFreest',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51mmZZWfATL._SX358_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=18GUA9giP0JZlqSohpizbPQ5L1gGUOyGI'),
  Book(
      id: 408,
      subject: 'Prosthodontics',
      title: 'Prosthodontic Treatment for Edentulous Patients',
      writer: 'Bolender, Eckert, Jacob, Fenton, Mericske-Stern Zarb (Author)',
      edition: '12th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/21LQ1VrhUBL._BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=14WDw1OPMczaiefnxevQCRk6OtqGraDe7'),
  Book(
      id: 409,
      subject: 'Prosthodontics',
      title: 'Esthetics of Anterior Fixed Prosthodontics',
      writer: 'Gerard Chiche (Author), Alain Pinault (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51%2B6qxRRGeL._SX396_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=115uFYf67PvOb2xBDdUmEaQrWMOCzqo5G'),
  Book(
      id: 410,
      subject: 'Oral Pathology',
      title: 'Shafer\'s Textbook of Oral Pathology',
      writer: 'B Sivapathasundharam',
      edition: '8th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41ohzTFEtjL._SX385_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''The periodic and timely revisions of Shafer’s Textbook of Oral Pathology have brought out a treatise, well conceived and written with the aim of updating students all necessary nuances of the specialty. The scope of the present edition is an extension of this goal aimed at understanding the disease processes at more fundamental level, the impetus being those in the maxillofacial region. The book highlights the aetiopathogenesis and clinical presentation of oral diseases and focuses on a variety of diseases commonly encountered in clinical practice.''',
      link:
          'https://drive.google.com/uc?export=download&id=1e5Q7i1F8JnkNtwBu2uE89WoGtjF8QG4v'),
  Book(
      id: 411,
      subject: 'Oral Pathology',
      title: 'Handbook of Oral Disease by Crispian Scully',
      writer: 'Crispian Scully (Author)',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51wYwOPa%2BmL._SX373_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1fJq3b1CBm9TSt5pwpSlLv2TL3d5QVCdW'),
  Book(
      id: 412,
      subject: 'Oral Pathology',
      title: 'Pocket Atlas of Oral Diseases',
      writer: 'george-laskaris (Author)',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41A972N-2kL._SX329_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=19vdthOKlwGE6dsAELhABf3jEOJU2KIcX'),
  Book(
      id: 413,
      subject: 'Oral Pathology',
      title: 'Oral Pathology: Clinical Pathologic Correlations',
      writer:
          'Joseph A. Regezi DDS MS (Author), James Sciubba DMD PhD (Author), Richard C. K. Jordan DDS MSc PhD FRCD(C) FRCPATH (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/412DN83R0BL._SX378_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1gr2jOnGjRMiZMp47T8NQ2BrlVYK3crPt'),
  Book(
      id: 414,
      subject: 'Oral Pathology',
      title: 'Color Atlas of Common Oral Diseases',
      writer: 'Robert Langlais (Author), Craig Miller (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51zk08emc8L._SX382_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1Q2hm_Nj9Ljb2-5RHX0tztP5-gfkc8VJ_'),
  Book(
      id: 415,
      subject: 'Oral Pathology',
      title: 'Contemporary Oral and Maxillofacial Pathology',
      writer:
          'Sapp DDS MS, J. Philip (Author), Eversole DDS MSD MA, Lewis Roy (Author), Wysocki DDS PhD, George W. (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/518ZHSF57AL._SX360_BO1,204,203,200_.jpg',
      rating: 1.0,
      description:
          '''This vibrant, full-color text provides the practical and up-to-date information readers need to understand and diagnose oral injuries and diseases. Organized in a consistent and logical format, it includes the latest discussions on oral pathology, as well as key content on neoplasia, immune-mediated disorders, developmental disorders, and oral manifestations of systemic conditions. Providing thorough discussions of the most common disorders, each chapter also includes a list of the recent review articles and classic publications that are related to the chapter\'s content. More than 900 photos and illustrations of the oral and maxillofacial region are included, and many photomicrographs are accompanied by simple color line drawings to aid in the detection of disease and abnormal cells.''',
      link:
          'https://drive.google.com/uc?export=download&id=1VJ7yvgt2rqBwhmSlW-t8Mr0MZar5vdaH'),
  Book(
      id: 416,
      subject: 'Oral Pathology',
      title: 'Oral and Maxillofacial Pathology',
      writer:
          'Neville DDS, Brad W. (Author), Damm DDS, Douglas D. (Author), Allen DDS MSD, Carl M. (Author), Chi DMD, Angela C. (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51ZWDHaO5wL._SX389_BO1,204,203,200_.jpg',
      rating: 4.4,
      description:
          '''See how to identify and effectively manage oral diseases! Oral and Maxillofacial Pathology, 4th Edition provides state-of-the-art information on the wide variety of diseases that may affect the oral and maxillofacial region. Over 1,400 radiographs and full-color clinical photos ― that’s more than any other reference ― bring pathologies and conditions to life. New to this edition is coverage of the latest advances in diagnosis and disease management, plus topics such as hereditary dental anomalies and oral lesions associated with cosmetic fillers. Written by well-known oral pathology educators Brad Neville, Douglas Damm, Carl Allen, and Angela Chi, this market leader is your go-to reference for the care of patients with oral disease!

Comprehensive contemporary overview of oral and maxillofacial pathology includes a brief description of each individual lesion or pathologic condition and the kind of pathologic process that it represents, followed by a discussion of its clinical and/or radiographic presentation, histopathologic features, and its treatment and prognosis.
Over 1,400 radiographs and full-color clinical photos facilitate the identification and classification of lesions and disease states.
Up-to-date concepts of pathogenesis and disease management help you understand the diseases that affect oral and maxillofacial structures, formulate an accurate diagnosis, and institute proper treatment.
Logical organization by body system or disease process makes it easy to look up specific conditions.
Comprehensive appendix on differential diagnosis organizes disease entities according to their most prominent or identifiable clinical features, helping you find and formulate differential diagnoses.
Information on forensic dentistry, methamphetamine, and gene mutations addresses some of today’s leading topics in oral pathology research.
Differential diagnosis case studies on the Evolve companion website include correct answers and rationales, offering more opportunities to improve your identification skills and diagnostic competency.
NEW cutting-edge content includes pathologies and conditions such as localized juvenile spongiotic gingival hyperplasia, oral lesions associated with cosmetic fillers, oropharyngeal carcinomas related to human papillomavirus (HPV), IgG4-related disease and mammary analogue secretory carcinomas, Globodontia, Lobodontia, Leishmaniasis, and Xanthelasma.
Over 130 NEW full-color photos and over 40 NEW radiographs bring common and uncommon disease states more clearly to life.''',
      link:
          'https://drive.google.com/uc?export=download&id=17DUnMRQJjb2uvrZPvEVNY4kApJg5bIIg'),
  Book(
      id: 417,
      subject: 'Oral Pathology',
      title: 'Cawson\'s Essentials of Oral Pathology and Oral Medicine',
      writer: 'Odell FDSRCS MSc PhD FRCPath, Edward W (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51NBShJ7tbL._SX389_BO1,204,203,200_.jpg',
      rating: 1.0,
      description:
          '''The new edition of this classic book continues to support a new generation of dental students in their understanding of the essential aspects of oral pathology, oral medicine and systemic disease, as they relate to the day-to-day practice of dentistry. Fully updated throughout with the latest diagnostic tests, treatment protocols and international guidelines, the book will be essential for all undergraduates studying dentistry as well as postgraduate examinations.

Brand new edition of the first textbook to integrate oral medicine, pathology and surgery in a practical, student-orientated fashion!
Friendly, accessible writing style provides ready access to essential information
Ample use of flow charts guide the student thorough the process of differential diagnosis for a range of conditions
Evidenced-based throughout to help facilitate safe clinical practice
Presents the latest national and international guidelines
Helpful self-assessment provides an indication of the level of understanding and problem solving abilities expected at an undergraduate level
Useful summary charts aid subject revision and understanding
Expanded to meet the higher-level of understanding and application of knowledge required of students today
Contains trusted PubMed ID references and websites to ensure relevance and immediacy
Updated design – with helpful colour coding – aids reader engagement and retention of facts
Improved illustration program helps clarify complex physiological processes and other challenging concepts''',
      link:
          'https://drive.google.com/uc?export=download&id=10pO0vT5tozzZtTCP0wWgzI4AhLrSucVE'),
  Book(
      id: 418,
      subject: 'Oral Pathology',
      title: 'Clinical Outline of Oral Pathology: Diagnosis and Treatment',
      writer: 'Lewis R. Eversole (Author)',
      edition: '4th',
      image:
          'https://i0.wp.com/pmphusa.com/wp-content/uploads/2018/11/clinical-outline-of-oral-pathology-cover.jpg',
      rating: 3.7,
      description:
          '''Clinical Outline of Oral Pathology, 4th edition, with full color images, integrates the clinical approaches to basic oral pathology, oral radiology, and oral medicine with a primary objective of providing students with a protocol for developing differential diagnoses. The text guides students through the process of evaluating patient responses and clinical signs so as to limit the differential and ultimately arrive at a definitive diagnosis, and developing appropriate management and treatment. Diseases of the oral cavity are categorized according to presenting signs and symptoms.''',
      link:
          'https://drive.google.com/uc?export=download&id=1ebE1d-Gke26VUwNzoZyfP75P5JsJBeWo'),
  Book(
      id: 419,
      subject: 'Oral Pathology',
      title: 'ORAL AND MAXILLOFACIAL PATHOLOGY',
      writer: 'Robert E. Marx, Diane Stern',
      edition: '1st',
      image:
          'https://prodimage.images-bn.com/pimages/9780867153903_p0_v1_s550x406.jpg',
      rating: 0.0,
      description:
          '''Written for the oral and maxillofacial surgeon and other dental and medical specialists who deal with pathologies in the oral cavity, midface, and neck, this clinically oriented book addresses the underlying mechanism of each disease and how that dictates its clinical and radiographic presentation; the process of determining a differential diagnosis for each disease or condition; specific treatment recommendations that the authors use or have researched as the most beneficial; and the prognosis after treatment. A specific aim of this book is to challenge many long-held concepts that are no longer valid, but that nevertheless have been passed down to succeeding generations of dental and medical school students. Another aim is to eliminate illogical and confusing terminology that only reinforces misconceptions about the underlying cause of specific diseases. Above all, the authors seek to increase the knowledge and understanding of oral and maxillofacial surgeons and others entrusted with the care of these patients.''',
      link:
          'https://drive.google.com/uc?export=download&id=14L9zsZdVz2KYRFXGYcuTkjFd2F1GQY1Y'),
  Book(
      id: 420,
      subject: 'Oral Pathology',
      title: 'General and Oral Pathology for Dental Hygiene Practice',
      writer: 'Sandra L Myers',
      edition: '1st',
      image:
          'https://i5.walmartimages.com/asr/0755b6bc-4904-4c0b-a36c-d11e668cbe1a_1.3e87ce32139f14ca23a82298c738f506.jpeg',
      rating: 0.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1wGpHOyralsj07ZlQLikJQShXc3frLxwh'),
  Book(
      id: 421,
      subject: 'Oral Pathology',
      title: 'Essentials of Pediatric Oral Pathology',
      writer:
          'Mayur Chaudhary  (Author), Shweta Dixit Chaudhary (Author), Asha Singh (Foreword), Minal Chaudhary (Foreword)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51gxOsoLseL._SX363_BO1,204,203,200_.jpg',
      rating: 0.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1BInuMTGPrZ2KImHhwAm7-ES4oODHA5kE'),
  Book(
      id: 422,
      subject: 'Oral Medicine / Radiology',
      title: 'Oral Medicine',
      writer:
          'Sergio Gandolfo MD DDS;Crispian Scully CBE MD PhD MDS MRCS BSc FDSRCS FDSRCPS FFDRCSI FDSRCSE FRCPath FMedSci FHEA FUCL FSB DSc DChD DMed (HC) Dr.hc;Marco Carrozzo MD DDS (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51wjg4mM3-L._SX354_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1VKsMn1bHygtcw81IfYvC6Zatao4PkSnq'),
  Book(
      id: 423,
      subject: 'Oral Medicine / Radiology',
      title: 'Oral Medicine (Medical Color Handbook Series)',
      writer: 'Michael A.O. Lewis (Author), Richard C.K. Jordan (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41keLVctPoL._SX331_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1PblHw7PGWpOyF10hp146pTSHLqIr3INp'),
  Book(
      id: 424,
      subject: 'Oral Medicine / Radiology',
      title: 'Clinical Manual For Oral Medicine And Radiology',
      writer: 'Ongole (Author)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51pdXEHDI9L._SX342_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1KgeYzq6hDRbmXMMCqB9mb4k5tyhs-ejh'),
  Book(
      id: 425,
      subject: 'Oral Medicine / Radiology',
      title: 'Burket\'s Oral Medicine',
      writer:
          'Martin S. Greenberg (Author), Michael Glick (Author), Jonathon A. Ship (Author)',
      edition: '11th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51W9lEtrkJL._SX344_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Oral health, as a part of dentistry, is an important field for research and development. Burket\'s Oral Medicine is a comprehensive text on dental or oral diseases that discusses various diseases of the oral cavity along with other fields of concern like pharmacology, oral cancer, salivary gland diseases, orofacial pain, headache, respiratory tract diseases and more.

Over 40 International experts have contributed to this collection of articles related to the diseases of the oral cavity. Each chapter in the Burket\'s Oral Medicine includes a case history affixed with a chart and a case representation for better understanding of the concepts.

The introduction is written by the authors Martin S Greenberg, Michael Glick and Jonathan A Ship, discuss at-length as how to gather relevant information about the patient\'s oral health history; how to examine the patient; how to review the symptoms; establishing the diagnosis; consultation process; and the treatment procedure.

The authors have provided illustrations and examples to determine a patient\'s situation and have also given techniques or methods to determine the risk involved in any such procedure.

Burket\'s Oral Medicine is one of the most comprehensive texts available on the topic of oral health and diseases that affect oral health in general. This text is beneficial for anyone who to gain an insight into the diseases affecting the oral cavity and the ways to tackle them. Burket\'s Oral Medicine was published by CBS in 2012 and is available in hardcover format.

Key Features:

Chapters and articles are written by various international experts and therefore, provide a thorough basis for studying oral health related matters.''',
      link:
          'https://drive.google.com/uc?export=download&id=1p_jmbHM2KDcCtMsoAeaCD5pHN0k-DxM_'),
  Book(
      id: 426,
      subject: 'Oral Medicine / Radiology',
      title: 'Clinical Oral Medicine And Pathology',
      writer: 'Jean M. Bruch  (Author), Nathaniel Treister (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/418Esrk2heL._SX336_BO1,204,203,200_.jpg',
      rating: 3.0,
      description:
          '''Clinical Oral Medicine and Pathology, is a clinically relevant and accessible resource for health care professionals that truly bridges the worlds of dentistry and medicine. This handbook of oral medicine and oral pathology serves as a highly readable guide for diagnosis and treatment of commonly encountered oral conditions. The volume is organized by grouping clinical entities under easily recognizable, diagnostically related headings and subheadings and allows the busy clinician to quickly reference and identify a lesion of interest. Concise descriptions of each entity provide background information and treatment recommendations while including specific guidelines on diagnosis, management, and follow-up. The authors of this text both have extensive training in the fields of oral pathology, dentistry, oral surgery and otolaryngology, and provide a comprehensive approach to the practice of oral medicine for all those who are likely to encounter diseases of the oral cavity in their daily practice.''',
      link:
          'http://93.174.95.29/main/1625000/80683a46322bc591ac20a9f8372fd05c/Jean%20M.%20Bruch%2C%20Nathaniel%20Treister%20%28auth.%29%20-%20Clinical%20Oral%20Medicine%20and%20Pathology-Springer%20International%20Publishing%20%282017%29.pdf'),
  Book(
      id: 427,
      subject: 'Oral Medicine / Radiology',
      title: 'Oral Medicine and Pathology at a Glance',
      writer:
          'Crispian Scully (Author), Oslei Paes de Almeida (Author), Jose Bagan (Author), Pedro Diz Dios (Author), Adalberto Mosqueda Taylor (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/513IekiJfGL._SX394_BO1,204,203,200_.jpg',
      rating: 3.1,
      description:
          '''Oral Medicine and Pathology At A Glance is a title in the highly popular at a Glance series. It provides a concise and accessible introduction and revision aid. Following the familiar, easy-to-use at a Glance format, each topic is presented as a double-page spread with key facts accompanied by clear diagrams, clinical photographs, and useful quick-reference tables, encapsulating essential information.
Systematically organized and succinctly delivered, Oral Medicine and Pathology At A Glance covers:

The most important conditions, by frequency and severity, in oral medicine and pathology
Commonly encountered oral lesions and pathologies
Oral manifestations of common systemic diseases
Differential diagnosis
Clinical management of these conditions
Oral Medicine and Pathology At A Glance is the ideal companion for all students of dentistry and recently qualified clinicians. In addition, through its focus on oral health care provision in general practice, the text will provide valuable insight for general dental practitioners wanting to update their knowledge of oral medicine and pathology, dental nurses, hygienists and therapists.''',
      link:
          'http://93.174.95.29/main/462000/e419e323d64d01ad8d2cbba1ecd7e748/Crispian%20Scully%2C%20Oslei%20Paes%20de%20Almeida%2C%20Jose%20Bagan%2C%20Pedro%20Diz%20Dios%2C%20Adalberto%20Mosqueda%20Taylor%20-%20Oral%20Medicine%20and%20Pathology%20at%20a%20Glance%20%282010%29.pdf'),
  Book(
      id: 428,
      subject: 'Oral Medicine / Radiology',
      title: 'Oral Medicine and Medically Complex Patients',
      writer: 'Peter B. Lockhart (Editor)',
      edition: '6th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51OPkiZJxwL._SX359_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Oral Medicine and Medically Complex Patients, Sixth Edition provides succinct, yet comprehensive information on in-hospital care and outpatient management of the medically complex dental patient, as well as the management of non-surgical problems of the maxillofacial region. Fully revised to include up-to-date information on procedures and medications, the Sixth Edition contains over 15 additional charts and tables for rapid reference and expanded coverage on maxillofacial prosthodontics and increasingly prevalent conditions, such as ONJ.

Oral Medicine and Medically Complex Patients follows a practical approach, organizing essential information into quickly referenced tables, easy-to-read diagrams and step-by-step procedures. Replete with examples of hospital charts, operative notes, and consultations, the book provides thorough coverage of the broad scope of clinical problems and patient populations encountered by dentists. A truly must-have resource Oral Medicine and Medically Complex Patients serves the needs of an increasing number of dental students, residents in general practice and specialty training, and practitioners engaged in the care of both hospitalized and ambulatory patients.''',
      link:
          'http://93.174.95.29/main/1000000/430a07399a673fed0fcca4403d5cf97f/%20-%20Oral%20Medicine%20and%20Medically%20Complex%20Patients%2C%20Sixth%20Edition-Wiley-Blackwell%20%282013%29.pdf'),
  Book(
      id: 429,
      subject: 'Oral Medicine / Radiology',
      title:
          'Contemporary Oral Medicine : A Comprehensive Approach to Clinical Practice',
      writer:
          'Camile S. Farah (Editor), Ramesh Balasubramaniam (Editor), Michael J. McCullough (Editor)',
      edition: '2019',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41oZq9C9ebL._SX350_BO1,204,203,200_.jpg',
      rating: 3.2,
      description:
          '''This book, written by world authorities in the field, is a comprehensive, up-to-date guide to the specialty of Oral Medicine, which is concerned with the diagnosis, prevention, and predominantly non-surgical management of medically related disorders and conditions affecting the oral and maxillofacial region. The pathophysiology, clinical presentation, diagnostic evaluation, and treatment of all relevant diseases and disorders are described with the aid of a wealth of clinical cases and illustrations that enable the reader to appreciate the diversity and potential complexity of Oral Medicine. In addition to the wide-ranging coverage of oral conditions, separate sections are devoted to bone and cutaneous pathology and to orofacial pain and its management, in addition to dental sleep medicine. The clinician who treats Oral Medicine patients will find this book to be an excellent aid to optimal management grounded in a sound knowledge of basic science and the dental and medical aspects of each disorder. In addition, it will serve as an outstanding textbook for undergraduate and postgraduate students.''',
      link:
          'http://93.174.95.29/main/2330000/1fb59031a65ae6bac57b010a2593d69f/Camile%20S.%20Farah%2C%20Ramesh%20Balasubramaniam%2C%20Michael%20J.%20McCullough%20-%20Contemporary%20Oral%20Medicine_%20A%20Comprehensive%20Approach%20to%20Clinical%20Practice-Springer%20%282019%29.pdf'),
  Book(
      id: 430,
      subject: 'Oral Medicine / Radiology',
      title: 'Nanostructures for Oral Medicine',
      writer:
          'Ecaterina Andronescu (Editor), Alexandru Mihai Grumezescu (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51wmHEyGHgL._SX404_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''Nanostructures for Oral Medicine presents an up-to-date examination of the applications and effects of nanostructured materials in oral medicine, with each chapter addressing recent developments, specific applications, and uses of nanostructures in the oral administration of therapeutic agents in dentistry.

The book also includes coverage of the biocompatibility of nanobiomaterials and their remarkable potential in improving human health and in reducing environmental pollution. Emerging advances, such as Dr. Franklin Tay\'s concept of a new nanotechnology process of growing extremely small, mineral-rich crystals and guiding them into the demineralized gaps between collagen fibers to prevent the aging and degradation of resin-dentin bonding is also discussed.

This work will be of great value to those who work in oral medicine, providing them with a resource to gain a greater understanding of how nanotechnology can help them create more efficient, cost-effective products. In addition, it will be of great interest to those who work in materials science who wish to gain a greater appreciation of how nanostructured materials are applied in this field.

Outlines the major uses of nanostructured materials for oral medicine, including the properties of each material discussed and how it should best be applied
Explores how nanostructured materials enable the creation of more effective drug delivery systems in oral medicine
Discusses how novel uses of nanostructured materials may be applied in oral medicine to create more effective devices''',
      link:
          'http://93.174.95.29/main/2065000/2c5255d8a41b3d7e226b9cc04b4ae075/Alexandru%20Mihai%20Grumezescu%20and%20Ecaterina%20Andronescu%20%28Eds.%29%20-%20Nanostructures%20for%20Oral%20Medicine.%20A%20volume%20in%20Micro%20and%20Nano%20Technologies-%20Elsevier%20%20%282017%29.pdf'),
  Book(
      id: 431,
      subject: 'Oral Medicine / Radiology',
      title: 'Step by Step Oral Radiology',
      writer: 'Ram Kumar Srivastava (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41nUn9IeTjL._SX320_BO1,204,203,200_.jpg',
      rating: 3.0,
      description: '''''',
      link:
          'http://93.174.95.29/main/2054000/b3d52971581279fef2f123f94ce646aa/Srivastava%20R.K.%20-%20Step%20by%20Step%20Oral%20Radiology.pdf'),
  Book(
      id: 432,
      subject: 'Oral Medicine / Radiology',
      title: 'Risk Assessment and Oral Diagnostics in Clinical Dentistry',
      writer:
          'Dena J. Fischer (Author), Nathaniel S. Treister (Author), Andres Pinto (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51PmR-efunL._SX350_BO1,204,203,200_.jpg',
      rating: 3.2,
      description:
          '''Many diseases can have an impact upon oral health and/or the safe delivery of dental care. Consequently, oral health care providers need to be comfortable with assessing the risk of providing dental care to their patients with systemic disease as well as the evaluation of oral conditions that may represent manifestations or consequences of systemic disease. Risk Assessment and Oral Diagnostics in Clinical Dentistry aims to enable the dental practitioner to comfortably and capably assess when medical conditions may impact dental care and diagnose oral conditions using routine testing modalities.

This clinical guide contains succinct and detailed text with visual aids regarding how to obtain and perform diagnostic tests, how to interpret these tests, and the implications of tests results upon the management of medically complex dental patients and patients with oral conditions. Color photographs show conditions, testing equipment, and test results. An appendix highlights the ten most common oral medicine disorders encountered in dental practice.''',
      link:
          'http://93.174.95.29/main/1001000/e3f3a5cdc69aad98622e74babed7cf56/Dena%20J.%20Fischer%2C%20Nathaniel%20S.%20Treister%2C%20Andres%20Pinto%28auth.%29%20-%20Risk%20Assessment%20and%20Oral%20Diagnostics%20in%20Clinical%20Dentistry-Wiley-Blackwell%20%282013%29.pdf'),
  Book(
      id: 433,
      subject: 'Oral Medicine / Radiology',
      title: 'White and Pharoah’s Oral Radiology',
      writer: 'Sanjay Mallya (Author), Ernest Lam (Author)',
      edition: '8th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41MzR6i%2B2XL._SX372_BO1,204,203,200_.jpg',
      rating: 3.4,
      description:
          '''Written specifically for dentists, White and Pharoah’s Oral Radiology: Principles and Interpretation 8th Edition incorporates over 1,500 high-quality radiographic images and illustrations to demonstrate core concepts and essential principles and techniques of oral and maxillofacial radiology. The new edition of this bestselling book delivers with state-of-the-art information on oral radiology principles and techniques, and image interpretation. Dental student will gain a solid foundation in radiation physics, radiation biology, and radiation safety and protection before introducing including specialized techniques such as MRI and CT. As well, students will learn how to recognize the key radiographic features of pathologic conditions and interpret radiographs accurately. The 8th edition also includes new chapters on Radiologic Anatomy, Beyond 3D Imaging, and Diseases Affecting the Structure of Bone. A practical guide to using today’s technology, this unique text helps your students provide state-of-the-art care!

Over 1,500 high quality dental radiographs, full color photos, and illustrations clearly demonstrate core concepts and reinforce the essential principles and techniques of oral and maxillofacial radiology.
Updated Extensive coverage of all aspects of oral and maxillofacial radiology includes the entire predoctoral curriculum.
A wide array of radiographic images including advanced imaging such as MRI and CT.
An easy-to-follow format simplifies the key radiographic features of each pathologic condition, including location, periphery, shape, internal structure, and effects on surrounding structures ― placed in context with clinical features, differential diagnosis, and management.
Expert contributors include many authors with worldwide reputations.
Case studies apply imaging concepts to real-world scenarios.
NEW! New editors Sanjay Mallya and Ernest Lam along with new contributors bring a fresh perspective on oral radiology.
NEW! Chapter! Beyond 3D Imaging introduces applications of 3D imaging such as stereolithic models.
NEW! Chapter Radiological Anatomy includes all radiological anatomy content allowing you to better visualize and understand normal appearances of structures on conventional and contemporary imaging, side-by-side.
NEW! Coverage of Diseases Affecting the Structure of Bone consolidated into one chapter to simplify foundational basic science information and its applications to radiologic interpretation.''',
      link:
          'http://93.174.95.29/main/2321000/65f03f55af6b3e5a1c0ec0410446c566/Sanjay%20Mallya_%20Ernest%20Lam%20-%20White%20and%20Pharoah%E2%80%99s%20Oral%20Radiology_%20Principles%20and%20Interpretation-Mosby%20%282018%29.pdf'),
  Book(
      id: 434,
      subject: 'Oral Medicine / Radiology',
      title: 'Color Atlas of Oral and Maxillofacial Diseases',
      writer:
          'Brad W. Neville DDS (Author), Douglas D. Damm DDS (Author), Carl M. Allen DDS MSD (Author), Angela C. Chi DMD (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41LB5dadgsL._SX390_BO1,204,203,200_.jpg',
      rating: 3.3,
      description:
          '''Introducing an essential new practical atlas for dental students and clinicians alike! The Color Atlas of Oral and Maxillofacial Diseases provides comprehensive, practical information on the most common oral and maxillofacial diseases and disorders. This new text uses a quick-access atlas format to help you easily look up clinical signs, diagnosis, and treatments. Nearly 750 high-quality images accompanied by brief narratives demonstrate exactly what clinical signs to look for – making an intervention as timely as possible. Written by four of the top dental authorities in the world, this concise resource is sure to become a clinical favorite. Expert Consult TM eBook version included with purchase. This enhanced eBook experience allows you to search all of the text, figures, and references from the book on a variety of devices

NEW! Quick-access atlas format makes it easy to look up clinical signs, diagnosis, and treatment of oral and maxillofacial diseases
NEW! Nearly 750 high-quality radiographs and color clinical photos facilitate the identification of lesions and diseases.
NEW! Comprehensive, focused coverage highlight diseases that may affect the oral and maxillofacial regions.
NEW! Full-color design and illustrations.
NEW! Logical organization reflects the sequence in which content is generally presented to predoctoral students.
NEW! Expert Consult TM eBook version included with purchase allows you to search all of the text, figures, and references from the book on a variety of devices''',
      link:
          'http://93.174.95.29/main/2283000/af6fedb1c8be2724f975ebfe6d3f992c/Brad%20W%20Neville_%20Douglas%20D%20Damm_%20Carl%20M%20Allen_%20Angela%20C%20Chi%20-%20Color%20Atlas%20of%20Oral%20and%20Maxillofacial%20Diseases-Elsevier%20%282018%29.pdf'),
  Book(
      id: 435,
      subject: 'Oral Medicine / Radiology',
      title: 'Color Atlas of Common Oral Diseases',
      writer: 'Robert P Langlais (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51zk08emc8L._SX382_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''Featuring over 800 clear, high-quality photographs and radiographic illustrations, this fully updated Fifth Edition of Color Atlas of Common Oral Diseases is designed throughout to help readers recognize and identify oral manifestations of local or systemic diseases. The new edition includes expanded and updated content and is enhanced by new images, new case studies, a stronger focus on national board exam prep, and more.
The bookâ€™s easy-to-navigate, easy-to-learn-from standard format consists of two-page spreads that provide a narrative overview on one page with color illustrations on the facing page. To integrate oral diagnosis, medicine, pathology, and radiology, the overviews emphasize the clinical description of oral lesions, cover the nature of various disease processes, and provide a brief discussion of cause and treatment options.''',
      link:
          'http://93.174.95.29/main/2230000/aaaebf6ff83bf23531125543349223f2/Robert%20Langlais%2C%20Craig%20Miller%20-%20Color%20Atlas%20of%20Common%20Oral%20Diseases-LWW%20%282016%29.pdf'),
  Book(
      id: 436,
      subject: 'Oral Medicine / Radiology',
      title: 'DENTAL RADIOGRAPHY Principles and Techniques',
      writer:
          'Joen Iannucci DDS MS (Author), Laura Jansen Howerton RDH MS (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51DYy7SdKKL._SX389_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''Set yourself up for success with this must-have oral radiography text. Dental Radiography: Principles and Techniques gives you a comprehensive foundation for the safe, effective use of radiation in the modern dental office. This combination textbook and training manual features easy-to-understand content combined with step-by-step techniques and a stellar art program to help you apply what you’ve learned to practice. Plus, new content focuses on pediatrics and the latest in digital and three-dimensional technology!

Comprehensive coverage offers all the information you need to know to prepare for board exams. 
Step-by-step procedures help ensure technique mastery and serve as a valuable reference tool. 
Technique Tips help you to recognize and prevent the most common performance pitfalls.
Quiz questions provide valuable self-assessment of important concepts. 
Key terminology is highlighted in chapter discussions and defined in a back-of-book glossary. 
Learning objectives and chapter summaries serve as goal-setting study tools.
EXPANDED! Content on pediatrics/adolescents, digital imaging, and three-dimensional radiography ensures that you’re prepared to practice in the modern dental office. 
UPDATED! Art program depicts the newest technology and equipment and includes new illustrations of anatomy and technique. 
UNIQUE! Helpful Hint boxes isolate challenging material and offer tips to aid your understanding.
NEW! Laboratory Manual provides workbook-style questions and activities to reinforce concepts and step-by-step instructions for in-clinic experiences. 
UNIQUE! Chapter on three-dimensional imaging helps you to prepare to enter private practice. 
UNIQUE! Full-color presentation helps you comprehend complex content.''',
      link:
          'http://93.174.95.29/main/2228000/a4daa88e6d1d20f2bccbdf80b779d49a/Joen%20Iannucci%2C%20Laura%20Jansen%20Howerton%20-%20Dental%20Radiography_%20Principles%20and%20Techniques-Saunders%20%282016%29.pdf'),
  Book(
      id: 437,
      subject: 'Oral Medicine / Radiology',
      title: '3D Radiology in Dentistry',
      writer:
          'Emanuele Ambu (Author), Roberto Ghiretti (Author), Riccardo Laziosi (Author)',
      edition: '',
      image: 'https://images-na.ssl-images-amazon.com/images/I/41vSKd-KNaL.jpg',
      rating: 3.9,
      description:
          '''A traditional radiography is a two-dimensional image of something that actually has three dimensions. At last, thanks to 3D radiological system with a small field of view we have the missing dimension, which exponentially amplifies our knowledge.
The CBCT (Cone Beam Computed Tomography) is a real breakthrough for dentistry because it offers many advantages: low radiation dose to patients, high definition with very small voxels, the possibility to see the tooth and the surrounding structures in three different planes, overcoming any anatomical overlapping.
It opens a new frontier, and allows us to make precise diagnosis where traditional tools were insufficient.
Reading the text we can see the enthusiasm and the passion with which the authors have produced this book. Each chapter is a font of information, every detail has been carefully examined, and each clinical case has been
extensively reported.
The introductory chapters provide the reader with the knowledge and basic tools to understand the CBCT.
Everything else is an atlas, highly enjoyable, which includes the use of CBCT in both clinical and surgical dentistry, and describes in details not only the diagnostic phase but also the operational use to program the individual case, and control the future outcome.''',
      link:
          'http://93.174.95.29/main/1401000/f27d44df50399155b610b0046357c3d1/Emanuele%20Ambu%2C%20Roberto%20Ghiretti%2C%20Riccardo%20Laziosi%20-%203D%20Radiology%20in%20Dentistry_%20Diagnosis%20Pre-Operative%20Planning%20Follow-Up-Elsevier%20%282013%29.pdf'),
  Book(
      id: 438,
      subject: 'Oral Medicine / Radiology',
      title: 'ORAL RADIOLOGY: PRINCIPLES AND INTERPRETATION',
      writer:
          'Stuart C. White DDS PhD (Author), Michael J. Pharoah DDS (Author)',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41sZbyL4KfL._SX389_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''With more than 1,000 high-quality radiographs and illustrations, Oral Radiology: Principles and Interpretation, 7th Edition visually demonstrates the basic principles of oral and maxillofacial radiology along with their clinical application. First, you’ll gain a solid foundation in radiation physics, radiation biology, and radiation safety and protection. Then you’ll learn intraoral and extraoral imaging techniques, including specialized techniques such as MRI and CT. The second half of the book focuses on how to recognize the radiographic features of pathologic conditions and interpret radiographs accurately. This edition also includes new chapters on forensics and cone-beam imaging. Written by oral radiology experts Stuart White and Michael Pharoah, this bestselling book helps you provide state-of-the-art care!

"This is a valuable source of information that should be in the armamentarium of any dentist in training or wanting to develop their competence in oral radiology."  BRITISH DENTAL JOURNAL VOLUME 217 NO. 2 JUL 25 2014

An easy-to-follow format simplifies the key radiographic features of each pathologic condition, including location, periphery, shape, internal structure, and effects on surrounding structures ― placed in context with clinical features, differential diagnosis, and management.
UPDATED information addresses the etiology and diagnosis of diseases and pathologic conditions in the orofacial region.
Updated coverage of all aspects of oral radiology includes the entire predoctoral curriculum.
A wide array of radiographs including advanced imaging such as MRI and CT.
Hundreds of drawings are updated and rendered in full color.
Case studies apply imaging concepts to real-world scenarios.
Expert contributors include many authors with worldwide reputations.
Chapter bibliographies and suggested readings make it easier to conduct further research.
NEW chapter on cone-beam imaging keeps you current with emerging field requirements.
NEW coverage of cone beam computed tomography (CBCT) includes more of the normal anatomy of cross-sectional images of the maxilla and mandible along with variations of normal anatomy.
NEW! An eBook version makes the content interactive and portable, and shows radiographs in high resolution.''',
      link:
          'http://93.174.95.29/main/1631000/5338c8342fe897e04ed132ab83571f67/Stuart%20C.%20White%2C%20Michael%20J.%20Pharoah%20-%20Oral%20Radiology_%20Principles%20and%20Interpretation-Mosby%20%282013%29.pdf'),
  Book(
      id: 439,
      subject: 'Oral Medicine / Radiology',
      title: 'ORAL AND MAXILLOFACIAL RADIOLOGY A DIAGNOSTIC APPROACH',
      writer: 'David MacDonald  (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51GfQFA5BXL._SX382_BO1,204,203,200_.jpg',
      rating: 3.0,
      description:
          '''To the dentist or maxillofacial practitioner, radiology is an essential diagnostic discipline and a valuable tool for treatment planning. Now more than ever, dentists are often the first to encounter lesions of the face and jaws and are frequently held liable for recognizing pathologies and other sites of concern. Oral and Maxillofacial Radiology: A Diagnostic Approach provides clinicians of varied disciplines and skill levels a practical and systematic approach to diagnosing lesions affecting the face and jaws. Firmly grounded in evidence-based research, the book presents a clear understanding of the clinical impact of each lesion within a prospective diagnosis.
Oral and Maxillofacial Radiology is logically organized, beginning with the basics of radiological diagnosis before discussing each of the advanced imaging modalities in turn. Modalities discussed include helical and cone-beam computed tomography, magnetic resonance imaging, positron emission tomography, and ultrasonography. Later chapters cover radiological pathologies of the jaw, and also those of the head and neck immediately outside the oral and maxillofacial region. Written by a recognized expert in the field, Oral and Maxillofacial Radiology contains a multitude of clinical images, practical examples, and flowcharts to facilitate differential diagnosis.''',
      link:
          'http://93.174.95.29/main/1405000/7ff6a21edb13aaf98c3d4d72b14b7902/David%20MacDonald%20-%20Oral%20and%20Maxillofacial%20Radiology_%20A%20Diagnostic%20Approach-Wiley-Blackwell%20%282011%29.pdf'),
  Book(
      id: 440,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Oral and Maxillofacial Surgery',
      writer:
          'Jonathan Pedlar BDS PhD FDSRCS(Eng) (Editor), John W. Frame PhD MSc BDS FDSRCS(Eng & Ed) (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/3162XN9Y2PL._BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=10BGGsHIfU2EpFRh65n9Kh01HFKeQ4k11'),
  Book(
      id: 441,
      subject: 'Oral and Maxillofacial Surgery',
      title:
          'Oral and Maxillofacial Medicine: The Basis of Diagnosis and Treatment',
      writer: 'Crispian Scully MD PhD (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51sCuulG5cL._SX366_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1J5C1chXZyZSJZRfSqIimwZB0pLfKscsU'),
  Book(
      id: 442,
      subject: 'Oral and Maxillofacial Surgery',
      title:
          'SUMMITT\'S FUNDAMENTALS OF OPERATIVE DENTISTRY A CONTEMPORARY APPROACH',
      writer: 'HILTON (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51tlGnCJFmL._SX384_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1jDpADu_Mpxe4m7-3_Mzc29L8-VIFV8qx'),
  Book(
      id: 443,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Oral Rehabilitation: A Case-Based Approach',
      writer: 'Iven Klineberg (Editor), Diana Kingston (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41CivYRRuML._SX395_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1yLOZL_LBTSlbk_uYqRb9jVosXL0-rsNp'),
  Book(
      id: 444,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Textbook of oral and maxillofacial surgery sm balaji',
      writer: 'S. M. Balaji (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51dIOavP72L._SX379_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''In the second edition of the book a detailed and authoritative exposition of basic principles of oral and maxillofacial surgery is presented in altogether 50 chapters under 12 sections. From basic oral surgical procedures encountered by general practitioner to advance and complex surgical procedures that need to be referred to an oral and maxillofacial surgery specialist, all are covered in sufficient detail with a judicious mix of text and illustrations including clinical photos, radiographs, CT and CBCTs

Consists of 2454 high resolution clinical images, for better clarity of the surgical concepts in step wise manner; 400 neatly drawn anatomical line illustrations, valuable for preparation during exams; and 150 tables and more than180 boxes for better understanding of the discussed core concepts
Includes chapters like Emergency Management and Preliminary Examination of a Trauma, Basic Principles in Management of Maxillofacial Injuries, Dentoalveolar Fractures, Mandibular Fractures, Maxillary Fractures, Orbitozygomatic complex, Naso-orbito-ethmoid Fractures and Frontal Fractures in Section XI on Maxillofacial Trauma
Contains chapters on Local Anaesthesia, Armamentarium, Impaction, Exodontia, Implantology, Orofacial Clefts and Distraction
Discusses important concepts like Definitions, History Taking, Radiodiagnosis, Biochemical, Haematological and Microbiological Investigations, Histopathological Investigation, Impaction, Endodontic Surgery
Covers recent advances: Bone Substitutes, Bioresorbable Plates, Lasers in Oral Surgery, Piezoelectric Surgery and Robotic Surgery along with a chapter on Medicolegal Considerations in Dentistry
– General Principles of Evaluation and Management

– Incisions and Flaps

– Haemorrhage and Shock

– Potential Spaces and their Management

– Odontogenic Tumours

– Nonodontogenic Tumours

– Oral Cancer

– Management of Jaw Tumour

– Anatomy of TMJ

– Internal Derangements and Condylar Dislocation

– TMJ Disorders

– TMJ Ankylosis''',
      link:
          'https://drive.google.com/uc?export=download&id=16Ct5tsoEdkBqUMQmy19I_ZTPSdD1lZaP'),
  Book(
      id: 445,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Current Therapy In Oral and Maxillofacial Surgery',
      writer:
          'Bagheri BS DMD MD FACS FICD, Shahrokh C. (Author), Bell DDS MD FACS, R. Bryan (Author), Khan MD DMD FACS, Husain Ali (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/510Je3wWkVL._SX411_BO1,204,203,200_.jpg',
      rating: 4.3,
      description:
          '''Written by expert surgeons and educators, Current Therapy in Oral and Maxillofacial Surgery covers the latest treatment strategies, surgical techniques, and potential complications in OMS. Emphasizing an evidence-based approach, it covers all 12 subspecialties of OMS, addressing topics from surgical principles to oral surgery, anesthesia, cranio-maxillofacial trauma surgery, head and neck surgery, maxillofacial reconstructive surgery, orthognathic surgery, pediatric craniofacial surgery including cleft lip and palate, temporomandibular joint disorders, facial plastic surgery including rhinoplasty and facelifts, obstructive sleep apnea, and oral and maxillofacial infections. At the end of each chapter, Pearls and Pitfalls summarize the authors\' insight, recommendations, and experience on that topic. Editor Dr. Shahrokh Bagheri is a noted professor, researcher, and speaker on OMS, and he leads an expert author team including Dr. R. Bryan Bell and Dr. Husain Ali Khan to help you master and apply the latest advances in OMS.

More than 1,200 full-color photos and 200 color line drawings illustrate concepts and provide visual guidance in clinical areas.
Comprehensive sections and chapters represent essential topics, the newest advances, and controversial topics.
Clinical coverage brings together the latest knowledge in OMS in a concise, easy-to-apply way.
Resident-specific coverage describes the wide array of subspecialties and treatments available in the armamentarium of the modern OMS.
A focus on complications ensures that you are knowledgeable in this important part of any therapy or surgical discipline.
Expert contributors include the "best of the best," featuring leading, well-established, and respected surgeons and educators writing on their areas of specialty and providing current treatment strategies.''',
      link:
          'https://drive.google.com/uc?export=download&id=1mq7BUBfUxfmWl0tdjQ9_jSeTz1Upx-4F'),
  Book(
      id: 446,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Contemporary Oral and Maxillofacial Surgery',
      writer:
          'Hupp DMD MD JD MBA, James R. (Author), Tucker DDS, Myron R. (Author), Ellis III DDS MS, Edward (Author)',
      edition: '7th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41evFW-Up1L._SX374_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''One of the most respected dental surgery books in the world, Contemporary Oral and Maxillofacial Surgery, 7th Edition helps you develop skills in evaluation, diagnosis, and patient management. This comprehensive text on oral surgery procedures features full-color photographs and drawings that show how to perform basic surgical techniques, including an overview of more advanced surgical procedures and the latest developments in dental implants, instrumentation, and current technology. A detailed patient evaluation section includes guidelines on when to refer patients to specialists and how to provide supportive postoperative care. New to this edition is a chapter focusing on anesthesia in greater depth than any of the previous editions. Written by well-known OMS educators James R. Hupp, and Edward Ellis III, and Myron R. Tucker, this book is a valuable reference for dentistry and dental hygiene students alike!

UPDATED! Chapter, Contemporary Implant Dentistry, includes new and updated implant surgical techniques and virtual planning.
UPDATED! Chapter, Treatment of Complex Implant Cases, features new and updated cases requiring more complex treatment, including bone augmentation surgery in combination with implants.
UPDATED! Coverage of Management of Sinus Disease updated outline of the fundamental principles for evaluation and treatment of the patient with sinus disease, including endoscopic therapy.
UPDATED! Coverage of Management of Medication-related Osteonecrosis of the Jaw outlines the fundamental principles for evaluation and treatment of the patient.
UPDATED! Facial Cosmetic Surgery chapter is organized by nonsurgical and surgical procedures, covering popular procedures such as dermal fillers, botox, facial resurfacing, browlift and forehead procedures, blepharoplasty, rhinoplasty, and rhytidectomy.
UPDATED! Content on implants, new instruments, and the latest technology help you treat your patients more effectively.
Basic techniques of evaluation, diagnosis, and medical management described in enough detail to facilitate immediate clinical application.
Excellent instrumentation chapter covers a wide variety of instruments and tray set-ups that OMS surgeons use.
Complex Exodontia chapter describes techniques for surgical tooth extraction, including the principles of flap design, development, management, and suturing, as well as open extraction of single- and multi-rooted teeth, multiple extractions, and concomitant alveoloplasty.
Hundreds of detailed, close-up photographs of intraoperative sites clarify textual descriptions
Coverage of complex OMS procedures give you a basic understanding of what you will face later in advanced OMS cases.
NEW! Chapter, Anesthesia in Dentistry focuses on anesthesia in greater depth than any of the previous editions including local anesthesia and nitrous oxide sedation.
NEW! Expert Consult TM eBook version included with purchase allows you to search all of the text, figures, and references from the book on a variety of devices''',
      link:
          'http://93.174.95.29/main/2340000/c27de4658de293cebe9db4915aacf036/James%20Hupp%2C%20Myron%20Tucker%2C%20Edward%20Ellis%20-%20Contemporary%20Oral%20and%20Maxillofacial%20Surgery-Mosby%20_%20Elsevier%20%282018%29.pdf'),
  Book(
      id: 447,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Peterson\'s Principles Of Oral & Maxillofacial Surgery',
      writer:
          'Michael Miloro (Author), GE Ghali (Author), Peter Larsen  (Author), Peter Waite (Author)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41K2FZtDR0L._SX386_BO1,204,203,200_.jpg',
      rating: 4.2,
      description:
          '''Peterson\'s Principles of Oral and Maxillofacial Surgery third edition, encompasses a wide range of diverse topics making it a unique text amongst the medical and dental specialties. The purpose of this concise, easy-to-read two-volume text is to provide an authoritative and currently referenced survey of the specialty of Oral and Maxillofacial Surgery. It contains the necessary information for clinicians and is an ideal reference text for preparation for board certification in the specialty''',
      link:
          'https://drive.google.com/uc?export=download&id=1VPRRxBeXkj34c44MDL3rQD_L4B4bHyz3'),
  Book(
      id: 448,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Textbook of Oral and Maxillofacial Surgery',
      writer: 'Malik Neelima Anil',
      edition: '4th',
      image: 'https://pictures.abebooks.com/isbn/9789385999871-us.jpg',
      rating: 4.7,
      description:
          '''This book is a complete guide to oral and maxillofacial surgery for dental students. Beginning with basic principles, each of the following sections discusses various disorders and infections, and their treatment. The fourth edition has been fully revised to provide the most up to date information and recent advances in the field. New topics have been included in this edition such as local anaesthesia, premalignant lesions, management of medical emergencies, cone beam computed tomography, piezosurgery, lasers, implants and robotic surgeries. The book is highly illustrated with line drawings, flowcharts, clinical photographs, and CT and MRI images, and also includes interactive DVD ROMs demonstrating techniques. Key Points Complete guide to oral and maxillofacial surgery for medical students and trainees Fully revised, new edition providing most up to date information in the field Fourth edition includes many new topics and accompanying DVD ROMs demonstrating techniques Previous edition published in 2012''',
      link:
          'https://drive.google.com/uc?export=download&id=1fLo0MoEezEqWAQEK79WeeVKOiuyF60PM'),
  Book(
      id: 449,
      subject: 'Oral and Maxillofacial Surgery',
      title:
          'Clinical Review of Oral and Maxillofacial Surgery: A Case-based Approach',
      writer: 'Bagheri BS DMD MD FACS FICD, Shahrokh C. (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51OiZsROMzL._SX392_BO1,204,203,200_.jpg',
      rating: 4.7,
      description:
          '''Organized around real patient scenarios, Clinical Review of Oral and Maxillofacial Surgery: A Case-based Approach, 2nd Edition, covers all the material you need to know for the board, in-service, and certification exams, while also preparing you to handle common patient situations in professional practice. Over 100 teaching cases are brought to life with an overview of the most common clinical presentations, physical examination findings, diagnostic tools, complications, treatments, and discussions of possible issues. This text covers the full scope of modern oral and maxillofacial surgery, while helping you focus on the conditions and disorders which are the most common, or have significant implications for modern clinical practice.

"I found this book expressly informative...I would most definitely recommend this book" Reviewed by British Dental Journal, Dec 2014

Case-based approach incorporates teaching around real patient scenarios to actively engage and raise your interest and retention of the information.
103 cases, many of which are new, represent the full scope of modern oral and maxillofacial surgery practice to encompass the most common and significant implications for modern clinical practice, including content emphasized on OMS boards and training exams.
Detailed illustrations including one or more radiographs, full-color clinical photographs, or drawings for the majority of cases provide a visual guide to conditions, techniques, diagnoses, and key concepts that will further enhance your understanding and retention of all content.
Content that’s perfect for all levels of study or practice covers both concepts and techniques that residents and pre-doctoral students can apply in the clinical setting, and the preparation tools necessary for oral and maxillofacial surgery boards and training/certification examinations.
NEW! Full-color illustrations and photos give you a better pictures of common surgical techniques and pathology.
NEW! Chapter 6: Dental Implant Surgery discusses the contemporary issues related to dental implants ― specifically the routine placement of maxillary and mandibular implants, sinus augmentation, zygoma implants, treatment of edentulism, guided implant surgery, extraction socket preservation, and implantology for the esthetic zone.
NEW! Section on cone beam computed tomography (CBCT) highlights the role of imaging from diagnosis to image guidance for many surgical procedures.
NEW! Section on the advantages of computer assisted surgery highlights virtual surgical planning for a patient who presents for combined surgical and orthodontic correction of his facial asymmetry and apertognathia.
NEW! Section on trigeminal neuralgia (TN) walks you through the diagnosis and possible treatments for a patient suffering from trigeminal neuralgia, the signs and symptoms that uniquely define the disorder, and the clinician’s ability to recognize the specific diagnostic pattern.
NEW! Section on neck dissection, an important aspect of head and neck cancer treatment, provides a case that involves a patient in which right selective neck dissection (I-III) was conducted on the right neck and a selective left neck dissection (I-V) was completed on the left side.
NEW! Section on dentoalveolar trauma presents a new case that takes you through diagnosing and treating a patient who presents with anterior maxillary alveolar segment fractures involving teeth #7-9, with lateral luxation and Ellis class III fracture tooth of #9, and an intraoral laceration of the upper lip.
NEW! Section on nasal septoplasty addresses a patient with a severely deviated nasal septum to the left, involving the quadrangular cartilage and the bony septum and how septoplasty can make a dramatic change in the patient\'s quality of life, by facilitating nasal airflow, allowing for better spontaneous drainage of the paranasal sinuses, possibly reducing mouth breathing, and reducing or eliminating the symptoms of snoring, and perhaps lessening the severity of the obstructive sleep apnea syndrome.''',
      link:
          'https://drive.google.com/uc?export=download&id=1o0wp_DkyzM1y8QkKiJr0Tr-n7O6gQwNO'),
  Book(
      id: 450,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Principles of Oral and Maxillofacial Surgery',
      writer:
          'Edited by  John Meechan , Edited by  J. Cowpe , Edited by  Mr UJ Moore , Edited by  Prof Thomson P J Thomson , Edited by  Dr KR Postlethwaite',
      edition: '5th',
      image:
          'https://d1w7fb2mkkr3kw.cloudfront.net/assets/images/book/lrg/9780/6320/9780632054381.jpg',
      rating: 3.0,
      description:
          '''First published over thirty years ago, this book has become the established introductory textbook for dental students. Carefully structured to provide a very wide range of information in appropriate depth, "Principles of Oral and Maxillofacial Surgery" is particularly valued for its accessibility and reader-friendly style. The text is further expanded and clarified throughout by a large number of illustrations. The new fifth edition has been completely updated to include the established pattern of maxillofacial surgery within the essential roots of undergraduate dental education and to reflect advances in the speciality including implants, anxiety management and the management of traumatic injuries, tumours and facial deformities.''',
      link:
          'https://drive.google.com/uc?export=download&id=1eC37HbVSHTuFpUlRtvy93uB_lhicwFk-'),
  Book(
      id: 451,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Oral and Maxillofacial Surgery Secrets',
      writer:
          'A. Omar Abubaker DMD PhD (Author), Kenneth J. Benson DDS (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51HbvhtQTBL._SX332_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Written in the question-and-answer style of the successful The Secrets Series®, the latest edition of Oral and Maxillofacial Surgery Secrets presents all of the most current clinical aspects of oral and maxillofacial surgery, including maxillofacial trauma, diagnosis of salivary gland disease, cysts and tumors, postoperative care, cleft lip and palate, oral and maxillofacial reconstruction, laser surgery, facial alloplastic implants, sleep apnea, and much, much more. The new edition has been completely updated by a diverse and distinguished group of contributors, and reflects recent advances in the field.''',
      link:
          'http://booksdl.org/get.php?md5=5f6e432d64f284a473c4d3f509c3d365&key=IEHBXHDC2ZMZ8JEA'),
  Book(
      id: 452,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Atlas of Operative Oral and Maxillofacial Surgery',
      writer: 'Christopher J. Haggerty  (Editor), Robert M. Laughlin  (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/513RReqxuWL._SX385_BO1,204,203,200_.jpg',
      rating: 4.9,
      description:
          '''Atlas of Operative Oral and Maxillofacial Surgery is an innovative, multidisciplinary, contemporary surgical atlas covering core aspects of oral and maxillofacial surgery, head and neck reconstructive surgery and facial cosmetic surgery. The text is constructed as a procedure-based surgical atlas with special emphasis placed on depicting surgical techniques with high-resolution color illustrations and images. Chapters are written by experts in their field and are designed to provide high-yield information pertaining to procedure indications, contraindications, pertinent anatomy, techniques, post-operative management, complications and key points. Each chapter concludes with a detailed photographic case report illustrating pertinent procedure specifics such as locations for incisions, anatomical planes of dissection, key steps in the procedure, radiographs findings and pre- and postoperative photographs.

Procedures are organized by sections to include: dentoalveolar and implant surgery, odontogenic head and neck infections, maxillofacial trauma surgery, orthognathic and craniofacial surgery, tempomandibular joint surgery, infections of the head and neck, facial cosmetic surgery, and pathology and reconstructive surgery.

The combination of concise text, more than 1,000 color clinical illustrations and images, and case reports makes the Atlas of Operative Oral and Maxillofacial Surgery a key reference to all oral and maxillofacial surgeons, head and neck surgeons, and facial plastic surgeons and will serve as a foundation for residency training, board certification and the recently implemented recertification examinations.''',
      link:
          'http://93.174.95.29/main/1316000/206472a9ec9c053f7c244c4721475caa/Christopher%20J.%20Haggerty%2C%20Robert%20M.%20Laughlin%20-%20Atlas%20of%20Operative%20Oral%20and%20Maxillofacial%20Surgery-Wiley-Blackwell%20%282015%29.pdf'),
  Book(
      id: 453,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'An Introduction to Oral and Maxillofacial Surgery',
      writer: 'by David A Mitchell  (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/514VG9bmjzL._SX382_BO1,204,203,200_.jpg',
      rating: 3.1,
      description: '''Highly Commended, BMA Medical Book Awards 2015

An Introduction to Oral and Maxillofacial Surgery encompasses the full range of oral and maxillofacial surgery. It also addresses the necessary core competencies for undergraduates and those pursuing basic specialist training.

The second edition now includes international perspectives. In the UK, oral and maxillofacial surgery is a unique discipline―the ninth of ten currently recognized surgical specialties―and trainees usually start from a dental qualification before gaining a medical one. In contrast, in Germany practitioners often start from a medical base and then obtain a dental degree while in North America they start from a dental base and may or may not become dually qualified.

The book’s initial chapters cater to all approaches of initial training and crucially bring them together in the specialist surgical sections. In chapters where the UK, US, and German perspectives are distinctly different, a section at the end has been added offering a specific perspective. However, where there is general consensus the international views have been integrated into the main body of text.

At the end of each chapter, where appropriate, readers will find relevant references and recommendations for further reading. This book can also be considered a definitive and consistently reliable source of information for those following the UK’s Intercollegiate Surgical Curriculum.''',
      link:
          'http://93.174.95.29/main/1315000/a25754dd58e31d5df6edbf35317e2ebd/David%20A%20Mitchell%20-%20An%20Introduction%20to%20Oral%20and%20Maxillofacial%20Surgery-CRC%20Press%20%282015%29.pdf'),
  Book(
      id: 454,
      subject: 'Oral and Maxillofacial Surgery',
      title:
          'Challenging Concepts in Oral and Maxillofacial Surgery : Cases with Expert Commentary',
      writer: 'Matthew Idle  (Editor), Andrew Monaghan (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51ucVGfcU7L._SX382_BO1,204,203,200_.jpg',
      rating: 3.0,
      description:
          '''Challenging Concepts in Oral and Maxillofacial Surgery details over 25 challenging and complex scenarios matched to the OMFS syllabus including frontal sinus fractures, reconstructive challenges following blast injuries to the facial soft tissue and skeleton, and reratocystic odontogenic tumours.

This case-based learning book is designed to be used by trainees and speciality registrars. Each case is supported by the commentary of a renowned expert in the field, allowing readers to improve their own management of these patients.

As the reader works through each case there are \'Clinical Tips\', \'Learning Points\' and \'Evidence Base\' boxes to enhance the learning process along with the \'Expert Commentary\', providing an inside track on how the experts approach challenging cases.

The range of topics discussed including three complex battlefield cases will be essential reading for trainees in oral and maxillofacial surgery and related specialties, such as otolaryngology, oral surgery, orthodontics, and dentistry.''',
      link:
          'http://93.174.95.29/main/1614000/a6e22108aaf3d2b2c1addca537c0fbd0/Matthew%20Idle%2C%20Andrew%20Monaghan%20-%20Challenging%20Concepts%20in%20Oral%20and%20Maxillofacial%20Surgery_%20Cases%20with%20Expert%20Commentary-Oxford%20University%20Press%20%282016%29.pdf'),
  Book(
      id: 455,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Oral and Maxillofacial Surgery:I',
      writer: 'Raymond J. Fonseca (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51A7L8UXabL._SX393_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''This trusted, three-volume resource covers the full scope of oral and maxillofacial surgery with up-to-date, evidence-based coverage of surgical procedures performed today.

NEW! Full color design provides a more vivid depiction of pathologies, concepts, and procedures.
NEW! Expert Consult website includes all of the chapters from the print text plus "classic" online-only chapters and an expanded image collection, references linked to PubMed, and periodic content updates.
NEW! Thoroughly revised and reorganized content reflects current information and advances in OMS.
NEW! New chapters on implants and orthognathic surgery cover the two areas where oral and maxillofacial surgeons have been expanding their practice.
NEW! Digital formats are offered in addition to the traditional print text and provide on-the-go access via mobile tablets and smart phones.''',
      link:
          'http://93.174.95.29/main/1596000/33a2c03fb90227ba2bf95c3d18eb9701/Raymond%20J.%20Fonseca%2C%20Marciani%2C%20Turvey%20-%20Oral%20and%20Maxillofacial%20Surgery.%20I-Saunders%20%282008%29.pdf'),
  Book(
      id: 456,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Oral and Maxillofacial Surgery:II',
      writer: 'Raymond J. Fonseca (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51A7L8UXabL._SX393_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''This trusted, three-volume resource covers the full scope of oral and maxillofacial surgery with up-to-date, evidence-based coverage of surgical procedures performed today.

NEW! Full color design provides a more vivid depiction of pathologies, concepts, and procedures.
NEW! Expert Consult website includes all of the chapters from the print text plus "classic" online-only chapters and an expanded image collection, references linked to PubMed, and periodic content updates.
NEW! Thoroughly revised and reorganized content reflects current information and advances in OMS.
NEW! New chapters on implants and orthognathic surgery cover the two areas where oral and maxillofacial surgeons have been expanding their practice.
NEW! Digital formats are offered in addition to the traditional print text and provide on-the-go access via mobile tablets and smart phones.''',
      link:
          'http://93.174.95.29/main/1596000/055e2531c623aece5734f57632de804a/Raymond%20J.%20Fonseca%2C%20Marciani%2C%20Turvey%20-%20Oral%20and%20Maxillofacial%20Surgery.%20II-Saunders%20%282008%29.pdf'),
  Book(
      id: 457,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Oral and Maxillofacial Surgery:III',
      writer: 'Raymond J. Fonseca (Author)',
      edition: '2nd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51A7L8UXabL._SX393_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''This trusted, three-volume resource covers the full scope of oral and maxillofacial surgery with up-to-date, evidence-based coverage of surgical procedures performed today.

NEW! Full color design provides a more vivid depiction of pathologies, concepts, and procedures.
NEW! Expert Consult website includes all of the chapters from the print text plus "classic" online-only chapters and an expanded image collection, references linked to PubMed, and periodic content updates.
NEW! Thoroughly revised and reorganized content reflects current information and advances in OMS.
NEW! New chapters on implants and orthognathic surgery cover the two areas where oral and maxillofacial surgeons have been expanding their practice.
NEW! Digital formats are offered in addition to the traditional print text and provide on-the-go access via mobile tablets and smart phones.''',
      link:
          'http://93.174.95.29/main/1596000/a4c04dd3f4bf9541a1a90d11903e34a6/Raymond%20J.%20Fonseca%2C%20Marciani%2C%20Turvey%20-%20Oral%20and%20Maxillofacial%20Surgery.%20III-Saunders%20%282008%29.pdf'),
  Book(
      id: 458,
      subject: 'Oral and Maxillofacial Surgery',
      title:
          'Operative Oral and Maxillofacial Surgery (Rob & Smith\'s Operative Surgery Series)',
      writer:
          'John D. Langdon (Editor), Mohan F. Patel (Editor), Robert Ord (Editor), Peter A. Brennan (Editor)',
      edition: '3rd',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51KYFMXxpzL._SX368_BO1,204,203,200_.jpg',
      rating: 3.2,
      description:
          '''Since the first edition was published, this book has become the standard text for trainees in oral and maxillofacial surgery preparing for their exit examinations (intercollegiate FRCS). This third edition represents a major advance with each chapter thoroughly revised and updated and relevant new topics added, such as robotics, laser resurfacing and face transplantation. Once again, the editors have selected renowned experts from around the world to author the chapters, ensuring that the book continues to reflect international best practices.''',
      link:
          'http://93.174.95.29/main/2177000/228e635507ac3b2dbe2ec720641414a0/%28Rob%20%26%20Smith%27s%20Operative%20Surgery%20Series%29%20John%20D.%20Langdon%2C%20Mohan%20F.%20Patel%2C%20Robert%20Ord%2C%20Peter%20A.%20Brennan%20-%20Operative%20Oral%20and%20Maxillofacial%20Surgery%2C%20Third%20Edition-CRC%20Press%20%282017%29.pdf'),
  Book(
      id: 459,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Clinician’s Handbook of Oral and Maxillofacial Surgery',
      writer: 'Daniel M. Laskin (Author, Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51c1mx5sAQL._SX312_BO1,204,203,200_.jpg',
      rating: 0.0,
      description:
          '''Developed and edited by one of the specialty s most respected and distinguished surgeons, this new and completely up-to-date handbook functions equally well as a survival manual for residents, as a quick reference for experienced clinicians, as a go-to source for managing emergency situations, and as a study guide for anyone preparing for board exams. It articulates the standards of care recognized by all licensed practitioners and the specific protocols that must be followed in providing treatment for the surgical patient. Spanning the full scope of oral and maxillofacial surgery, chapters address routine aspects of care such as doing a proper history and physical examination, interpreting lab tests and radiographs, and managing complications of dentoalveolar surgery; specialized treatment for patients with infections, cysts and tumors, salivary gland disease, neck masses, and other forms of oral and maxillofacial pathology; and protocols for managing anesthetic and medical emergencies, severely traumatized patients, and those with other life-threatening injuries. The authors are recognized authorities who know the most pressing questions that are likely to arise in the clinic and operating room as well as the answers to them. Compact and portable, this handbook is a ready source of essential information for the busy clinician.''',
      link:
          'http://93.174.95.29/main/2296000/02b6b77b7ea5be19e4fe6bd7bb9567dc/%282%29%20Daniel%20M.%20L%20-%20Clinician%E2%80%99s%20Handbook%20of%20Oral%20and%20Maxillofacial%20Surgery.pdf'),
  Book(
      id: 460,
      subject: 'Oral and Maxillofacial Surgery',
      title: 'Essentials of Oral and Maxillofacial Surgery',
      writer:
          'M. Anthony Pogrel (Editor), Karl-Erik Kahnberg (Editor), Lars Andersson (Editor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51s2XD-HGsL._SX352_BO1,204,203,200_.jpg',
      rating: 3.1,
      description:
          '''Essentials of Oral and Maxillofacial Surgery is the key textbook for all undergraduate dentistry students and trainees starting out in oral and maxillofacial surgery, oral surgery and surgical dentistry. Condensed and revised from the major reference work Oral and Maxillofacial Surgery, all revisions have been made by the editors in order to bring the text up-to-date and accessible for a student audience.

The book\'s coverage extends from basic principles such as patient evaluation, radiographic imaging, and surgical instruments, to specific conditions and procedures, from tooth extraction and endodontic surgery to trauma, implants, dentofacial deformities and orofacial pain. It also offers:

A companion website with downloadable figures and MCQs to test your knowledge
Over 600 colour photographs, radiographs and explanatory line drawings to illuminate the text
Contributions from an international group of authors, distilled by an expert editor team''',
      link:
          'http://93.174.95.29/main/1404000/3938b31980c5e5b75fc853e9704e8e3a/M.%20A.%20Pogrel%2C%20K.-E.%20Kahnberg%2C%20L.%20Andersson%20%28eds.%29%20-%20Essentials%20of%20Oral%20and%20Maxillofacial%20Surgery-Wiley-Blackwell%20%282014%29.pdf'),
  Book(
      id: 461,
      subject: 'MCQ Dental',
      title: 'Dental Pulse Set - (Vol-1 and Vol-2)',
      writer: 'K. Satheesh Kumar Reddy & M. Swapna (Author)',
      edition: '9th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51zDNad9XuL._SX379_BO1,204,203,200_.jpg',
      rating: 5.0,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1rf2Ai38x7sAjTL8hLoxCMyM55b7jMVni'),
  Book(
      id: 462,
      subject: 'AIIMS/NEET PG',
      title: 'AIIMS GK with Logical Thinking',
      writer: 'Dr. MD. Usmangani Ansari',
      edition: '(2016-17)',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51gmiiRkeEL._SX318_BO1,204,203,200_.jpg',
      rating: 3.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1RuUx61HQbE9cV3nzCKJ0GBaD2UF_6w2z'),
  Book(
      id: 463,
      subject: 'AIIMS/NEET PG',
      title: 'PHOTON 20 SUBJECTS IMAGE BASED QUESTIONS (PB 2016)',
      writer: 'JAIN V. (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41J4MxYicfL._SX279_BO1,204,203,200_.jpg',
      rating: 3.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=17mDC3kRCKAOx1OsZ6orKswebC-46v4H3'),
  Book(
      id: 464,
      subject: 'USMLE',
      title: 'First Aid for the USMLE Step 1 2019',
      writer: 'Tao Le  (Author), Vikas Bhushan  (Author)',
      edition: '29th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51eiIrfDUlL._SX389_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1Vt0UxB9AAAvFdqpG-uH1yk_1RMTJ1KNN'),
  Book(
      id: 465,
      subject: 'USMLE',
      title: 'First Aid for the USMLE Step 2 CS',
      writer:
          'Tao Le  (Author), Vikas Bhushan  (Author), Mae Sheikh-Ali (Author), Kachiu Cecilia Lee (Author)',
      edition: '5th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51SAOsid4uL._SX388_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=12gnwYyKixwwlxvg0OJcfgxiTV4sdvX3m'),
  Book(
      id: 466,
      subject: 'USMLE',
      title: 'First Aid for the USMLE Step 3',
      writer: 'Tao Le  (Author), Vikas Bhushan  (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51QlmKFe8HL._SX390_BO1,204,203,200_.jpg',
      rating: 4.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1e4BmNmVG05jijZYNSEvfoCl6rcsJA9GX'),
  Book(
      id: 467,
      subject: 'USMLE',
      title: 'USMLE Step 1 Lecture Notes 2018: 7-Book Set (Kaplan Test Prep)',
      writer: '',
      edition: '2018',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51WXKYpA6vL._SY410_BO1,204,203,200_.jpg',
      rating: 3.7,
      description: '''Series: Kaplan Test Prep
Paperback: 2608 pages
Publisher: Kaplan Publishing; 1 edition (December 5, 2017)
Language: English
ISBN-10: 150622122X
ISBN-13: 978-1506221229''',
      link:
          'http://93.174.95.29/main/2173000/5bac6a633646233dfb6b9c4f82a4d462/%28Kaplan%20Test%20Prep%29%20Kaplan%20Medical%20-%20USMLE%20Step%201%20Lecture%20Notes%202018_%207-Book%20Set-Kaplan%20Publishing%20%282018%29.pdf'),
  Book(
      id: 468,
      subject: 'USMLE',
      title: 'YALE-G FIRST AID:CRUSH USMLE STEP 2CK & Step 3',
      writer:
          'Yale Gong MD  (Author), Mathew Warner MD; Magdalini Tsintou MD (Contributor)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51l64qGDe7L._SX383_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Author\'s notes: Author\'s bookstore-website (www.usmle-yaleg.com) offers important free Yale-G\'s Rep-Chapters+images.pdf, Errata/Updates, international shipping, and deep discount. This "Yale-G First Aid (Ed4)" has 25-30% updates from the 3rd-edition of Yale-G\'s Refined Clinical Review for the USMLE Step 2 & 3 based on readers\' feedbacks and www.uptodate.com. Please kindly communicate by emails if you are dissatisfied with anything before posting irresponsible/harmful reviews. According to those frank feedbacks, this book has really collected the most high-yield and complete clinical knowledge particularly needed for the USMLE Step 2 CK and Step 3. If you have been looking for the equivalent of "First Aid for the USMLE Step 1" without success, this one can be it! This can be your "bible" for the USMLE Step 2 CK and Step 3. All high yield materials are in here. This book is certainly a must for USMLE Step 2 CK and Step 3 if you aim at high scores! Important features of this book include: 1. Systematic, concise summaries of most diseases and disorders that are most frequently tested in the USMLE Step 2 CK and Step 3. 2. Well-organized contents, more than 100 tables for summaries and differential diagnoses, and necessary details of high-yield "orderly steps" in the diagnosis and management of major diseases. All the "PEARLS", bold and colored areas are high-yield contents that are likely to be seen in the USMLE examinations. 3. > 600 refined, fundamental HYQs in real-examination format. 4. 155 selected high-yield clinical color images with brief diagnostic features. After a thorough digestion of this book (read twice), plus the best Qbank at "www.usmleworld.com" twice, you will be ready to crush the USMLE Step 2 CK and Step 3 with high scores! The author team is so confident of this as to offer the "money back guarantee" for any rare failure of the USMLE Step 2 CK. This book is your ticket to the USMLE and ECFMG certification! Best wishes!''',
      link:
          'https://drive.google.com/uc?export=download&id=1WDO1w9HB0nQpYziPWAbdqa31FXI1On-D'),
  Book(
      id: 469,
      subject: 'USMLE',
      title: 'USMLE STEP 2 CK: PEDIATRICS',
      writer: 'Kaplan Medical (Author)',
      edition: '2019',
      image:
          'https://0.academia-photos.com/attachment_thumbnails/58161775/mini_magick20190111-27516-j2d1o7.png',
      rating: 3.9,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1NIWmxkyWSNWpD1HrTnpJtApWvxCjSR0V'),
  Book(
      id: 470,
      subject: 'USMLE',
      title: 'USMLE Step 1 Secrets in Color',
      writer: 'Brown MD, Thomas A. (Author), Sonali J Bracken (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/511TgrKiNLL._SX352_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''Concise and easy-to-use, USMLE Step 1 Secrets provides the most effective, high-yield review you need for achieving success on this high-stakes exam. Presented in the popular Secrets Q&A format, this bestselling USMLE review book features questions and short answers along with case scenarios to prepare you for the vignette-style USMLE exam.

A case-based approach and abundant clinical context help prepare for the vignette-style of the USMLE exam.
Renowned USMLE review author Dr. Thomas Brown and Dr. Sonali Bracken bring together their expertise with a team of medical student reviewers and authors to provide the most current overview of board-tested content.
Figures, tables, and summary boxes provide a visual and concise overview of important board-relevant content.
New color images added throughout―including those found in a new chapter covering high-yield dermatology and pathology―enhance visual review of important, board-relevant images.
New larger trim size for improved note-taking and easy review of this comprehensive, high-yield review.
Student Consult eBook version included with purchase. This enhanced eBook experience includes access -- on a variety of devices -- to the complete text, images, and references from the book.''',
      link:
          'http://93.174.95.29/main/1643000/2a265ca1360ff71f6e85a08601fdba83/Thomas%20A.%20Brown%20MD%2C%20Sonali%20J.%20Bracken%20-%20USMLE%20Step%201%20Secrets%20in%20Color%2C%204e-Elsevier%20%282016%29.pdf'),
  Book(
      id: 471,
      subject: 'USMLE',
      title: 'Kaplan Medical USMLE Step 3 Qbook',
      writer: 'Kaplan Medical (Author)',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41LXfhLHHNL._SX380_BO1,204,203,200_.jpg',
      rating: 3.9,
      description: '''Are you ready for Step 3 of the USMLE?

USMLE Step 3 Qbook from Kaplan Medical -- -the leading provider of test preparation for medical licensure -- provides you with 850 high-yield exam-style questions, plus Kaplan Medical\'s highly effective test-taking strategies.

Prepare
with high-yield medical content tested on the exam.

Practice
with hundreds of test-like questions and a complete explanation for every answer choice.

Pass
with Kaplan Medical\'s powerful strategies for effectively managing your time and minimizing stress.''',
      link:
          'http://93.174.95.29/main/552000/3093688755328632f0258d0b11a1a87c/Kaplan%20Medical%20-%20Kaplan%20Medical%20USMLE%20Step%203%20Qbook%20%28Kaplan%20USMLE%20Qbook%29-Kaplan%20Publishing%20%282004%29.pdf'),
  Book(
      id: 472,
      subject: 'USMLE',
      title:
          'USMLE Step 2 CK Lecture Notes 2019: Obstetrics/Gynecology (Kaplan Test Prep)',
      writer: '',
      edition: '2019',
      image: 'https://images-na.ssl-images-amazon.com/images/I/51jqKZescbL.jpg',
      rating: 3.9,
      description: '''File Size: 34708 KB
Print Length: 559 pages
Publisher: Kaplan Publishing (October 2, 2018)
Publication Date: October 2, 2018
Sold by: Amazon Digital Services LLC
Language: English
ASIN: B07CL4KYFP''',
      link:
          'http://93.174.95.29/main/2290000/6abdf54e52838e440e60a3ddec9f0c3e/%28Kaplan%20Test%20Prep%29%20Elmar%20Peter%20Sakala%2C%20Joshua%20P.%20Kesterson%2C%20Alvin%20Schamroth%20-%20USMLE%20Step%202%20CK%20Lecture%20Notes%202019_%20Obstetrics_Gynecology-Kaplan%20Publishing%20%282019%29.pdf'),
  Book(
      id: 473,
      subject: 'USMLE',
      title: 'Kaplan Test USMLE Step 2 CK Lecture Notes 2019 Surgery',
      writer: '',
      edition: '2019',
      image:
          'https://0.academia-photos.com/attachment_thumbnails/58161771/mini_magick20190111-23130-cyk720.png',
      rating: 3.7,
      description: '''''',
      link:
          'https://drive.google.com/uc?export=download&id=1yl2tM9hTROJdvF1npl1NADeAbZhOMzQd'),
  Book(
      id: 474,
      subject: 'USMLE',
      title: 'Kaplan Medical USMLE Step 1 Qbook',
      writer: 'Kaplan (Author)',
      edition: '4th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41t7xfuAsKL._SY298_BO1,204,203,200_.jpg',
      rating: 4.7,
      description: '''''',
      link:
          'http://93.174.95.29/main/516000/a28cc4b5e767d485cdee6bcb9ff808f3/Kaplan%20-%20Kaplan%20Medical%20USMLE%20Step%201%20Qbook-Kaplan%20Publishing%20%282008%29.epub'),
  Book(
      id: 475,
      subject: 'USMLE',
      title: 'KAPLAN USMLE Step 1 Review Volume 1 (General Principles Book1)',
      writer: 'Kaplan (Author)',
      edition: '1st',
      image:
          'https://chancesforyouth.com/wp-content/uploads/2018/07/824d053af3a8881d3139ac7aeae0761c.jpg',
      rating: 4.1,
      description: '''''',
      link:
          'http://93.174.95.29/main/524000/9846b5481a00acbd230d9b8e8c7baa9d/Kaplan%20Medical%20-%20USMLE%20Step%201%20Review%20-%20Home%20Study%20Program%20-%20Vol%20I%20-%20General%20Principles%201-Kaplan%20Medical%20%282008%29.pdf'),
  Book(
      id: 476,
      subject: 'USMLE',
      title: 'KAPLAN MEDICAL USMLE STEP 1 REVIEW VOLUME 2',
      writer: 'Kaplan (Author)',
      edition: '1st',
      image: 'https://cdn.ketab.io/covers/1/109973-n.jpg',
      rating: 4.1,
      description: '''''',
      link: 'https://www.acloudfiles.com/f7d9213fb85b2aa7'),
  Book(
      id: 477,
      subject: 'USMLE',
      title: 'KAPLAN MEDICAL USMLE STEP 1 REVIEW VOLUME 3',
      writer: 'Kaplan (Author)',
      edition: '',
      image:
          'https://i.pinimg.com/474x/9b/b1/b5/9bb1b5c5e975460b865467a04ca74e22.jpg',
      rating: 4.1,
      description: '''''',
      link:
          'http://93.174.95.29/main/427000/66a7a71e6146ae7dc7c57e68f8aeeb18/Kaplan%20Medical%20-%20USMLE%20Step%201%20Review%20-%20Home%20Study%20Program%20-%20Volume%20III%20-%20Organ%20Systems%201-Kaplan%20Medical%20%282008%29.pdf'),
  Book(
      id: 478,
      subject: 'USMLE',
      title: 'KAPLAN MEDICAL USMLE STEP 1 REVIEW VOLUME 4',
      writer: 'Kaplan (Author)',
      edition: '',
      image:
          'https://i.pinimg.com/474x/03/d4/1d/03d41d0138fcb89c9f2f4adf3d7f7119.jpg',
      rating: 4.1,
      description: '''''',
      link:
          'http://93.174.95.29/main/426000/679649598b111553b2eddbc1320406f4/Kaplan%20Medical%20-%20USMLE%20Step%201%20Review%20-%20Home%20Study%20Program%20-%20Volume%20IV%20-%20Organ%20Systems%202-Kaplan%20Medical%20%282008%29.pdf'),
  Book(
      id: 479,
      subject: 'USMLE',
      title: 'BECKER USMLE Step 1 Anatomy',
      writer: 'Dr. Jack Wilson (Author)',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41sX7a06bRL._SY330_BO1,204,203,200_.jpg',
      rating: 4.1,
      description:
          '''Anatomy review text tailored to passing the USMLE. Contains text and many detailed color figures.''',
      link:
          'https://ia801503.us.archive.org/2/items/3bbbeeeecccckkkeeeerrrruussmmllesttteeeppp1anatomypdf/3BbbeeeEcccCkkKeeeErrrR%20UuSsMmLlE%20Sttteeeppp%201%20Anatomy%20PDF.pdf'),
  Book(
      id: 480,
      subject: 'USMLE',
      title:
          'Becker Professional Education, USMLE, Step 1, Behavioral Science, Epidemiology, & Biostatistics',
      writer: '',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51enyrlB7wL._SX362_BO1,204,203,200_.jpg',
      rating: 3.1,
      description: '''Brand new 2016 edition!''',
      link:
          'https://ia801406.us.archive.org/12/items/4bbbeeeccckkkeeeerrrussssmmmllleeestep1b.scienceepi..bio/4BbbEeeCccKkkEeeeRrr%20UsssSMmmLllEee%20Step%201%20B.Science%20Epi..Bio.pdf'),
  Book(
      id: 481,
      subject: 'USMLE',
      title: 'BECKER USMLE Step 1 Biochemistry, Genetics',
      writer: '',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51g2i8Vom3L._SX362_BO1,204,203,200_.jpg',
      rating: 4.1,
      description: '''''',
      link:
          'https://ia801502.us.archive.org/7/items/5bbbeeeccckkkeeeerrruuusssmmmllleeestep1biogenetics/5BbbEeeCccKkkEeeerrR%20UuuSssMmmLlleeE%20Step%201%20BioGenetics.pdf'),
  Book(
      id: 482,
      subject: 'USMLE',
      title: 'BECKER USMLE Step 1 Immunology, Microbiology',
      writer: '',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51Jm7VP6NxL._SY373_BO1,204,203,200_.jpg',
      rating: 4.0,
      description: '''''',
      link:
          'https://ia801505.us.archive.org/33/items/6beeeeecccckkkkkeeeerrruuussssmmmllleeestep1immmicro/6BeeeeECcccKkkkkEeeeRrr%20UuusssSMmmLllEee%20Step%201%20ImmMicro.pdf'),
  Book(
      id: 483,
      subject: 'USMLE',
      title: 'BECKER USMLE Step 1 Pharmacology',
      writer: '',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51IcNVUs%2BaL._SX373_BO1,204,203,200_.jpg',
      rating: 4.1,
      description: '''''',
      link:
          'https://ia801409.us.archive.org/18/items/bbbbeeeecccckkkkeeeerrrruuuuussssmmmmlllleeestep1pharmac/BbbbeeeEcccCkkkKEeeerrrR%20UuuuuSsssMmmmlllLeeE%20Step%201%20Pharmac.pdf'),
  Book(
      id: 484,
      subject: 'USMLE',
      title: 'BECKER USMLE Step 1 Physiology',
      writer: '',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51mTMnh4iML._SX279_BO1,204,203,200_.jpg',
      rating: 4.1,
      description: '''''',
      link:
          'https://ia801505.us.archive.org/1/items/beeeeecccckkkkeeeeeerrruussmmlleestep1phy/BEeeeeCccckkkKeeEeeeRrr%20UuSsMmlLee%20Step%201%20Phy.pdf'),
  Book(
      id: 485,
      subject: 'USMLE',
      title: 'BECKER USMLE Step 1 Pathology Volume 1',
      writer: '',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51QGPDFsbhL._SX362_BO1,204,203,200_.jpg',
      rating: 4.0,
      description: '''''',
      link:
          'https://archive.org/download/7bbbbeeeecccckkkkeeerrrrruuusssmmmmlllleeeestep1path/7BbbbeeeECcccKkkkEeerrrrR%20UuussSmmmMlllLeeeE%20Step%201%20Path.pdf'),
  Book(
      id: 486,
      subject: 'USMLE',
      title: 'BECKER USMLE Step 1 Pathology Volume 2',
      writer: '',
      edition: '',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51QGPDFsbhL._SX362_BO1,204,203,200_.jpg',
      rating: 4.1,
      description: '''''',
      link:
          'https://ia801405.us.archive.org/17/items/8bbbbecccckkkeeerrruuusssmmmllleeestep1patho/8BbbbEcccCkkKeeErrR%20UuuSssMmmLllEee%20Step%201%20Patho.pdf'),
  Book(
      id: 487,
      subject: 'Other Clinical',
      title: 'Bates\' Guide to Physical Examination and History Taking',
      writer: 'Bickley MD FACP, Lynn S. (Author)',
      edition: '12th',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51vQy0rK%2BvL._SX383_BO1,204,203,200_.jpg',
      rating: 3.5,
      description:
          '''Bates’ Guide to Physical Examination and History Taking provides authoritative, step-by-step guidance on performing the patient interview and physical examination, applying clinical reasoning, shared decision-making, and other core assessment skills—all based on a firm understanding of clinical evidence.
This highly regarded text includes fully illustrated, step-by-step techniques that outline the correct performance of the physical examination and an easy-to-follow two-column format featuring examination techniques on the left and abnormalities (clearly indicated in red) with differential diagnoses on the right. Bates’ also includes a unit on special populations, covering special stages in the life cycle—infancy through adolescence, pregnancy, and aging.
Clinical pearls , printed in blue, highlight key points throughout the text.
Text boxes help readers quickly find important summaries of clinical conditions and tips for challenging examination techniques.
Many new and updated photographs and illustrations support the text, and figures are now numbered for easy identification and reference.
Rewritten chapter on evaluating clinical evidence clarifies key concepts to ensure student understanding.
Revised and expanded chapter on the skin, hair, and nails includes new dermatology photographs and provides the framework for assessing common lesions and abnormalities.
Updated behavior and mental status chapter now references DSM-5 .
Significantly revised information on obesity and nutrition counseling; cardiovascular risk factor screening and new clinical guidelines; new screening guidelines for breast cancer, colon cancer, Papanicolau smears, and stroke risk factors; updated information on STIs; new geriatric assessment tools; and much more.
New life cycle content , including an increased emphasis on cardiovascular health promotion and child development; updated pregnancy topics such as weight gain, substance abuse, and intimate partner violence; and new information on the older adult, including frailty, immunizations, cancer screening, cognitive decline and dementia screening, and a new algorithm for falls prevention.
Bates’ Guide to Physical Examination and History Taking is the #1 choice for complete, authoritative guidance on mastering every aspect of the all-important physical examination.

Don’t Miss These Additional Resources also Available for Purchase:

Bates’ Pocket Guide to Physical Examination and History Taking, Eighth Edition
The Pocket Guide is an abbreviated version of the Bates’ twelfth edition textbook, designed for portability and convenience at the bedside.
Bates’ Visual Guide to Physical Examination (www.batesvisualguide.com)
Recently refilmed, these 18 volumes of examination videos (as well as 10 additional OSCEs) depict experienced clinicians conducting each of the regional examinations. The videos demonstrate visually the varying techniques of inspection, palpation, percussion, and auscultation in the regional examinations and special populations.''',
      link:
          'http://93.174.95.29/main/1535000/26a50381b9dcb11d247481722bb6b13d/Lynn%20S.%20Bickley%20-%20Bates%E2%80%99%20Guide%20to%20Physical%20Examination%20and%20History%20Taking-LWW%20%282016%29.pdf'),
  Book(
      id: 488,
      subject: 'Other Clinical',
      title:
          'Medical Student Survival Skills: History Taking and Communication Skills',
      writer: 'Philip Jevon (Author), Steve Odogwu (Author)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/41WVwghUFLL._SX322_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''Medical students encounter many challenges on their path to success, from managing their time, applying theory to practice, and passing exams. The Medical Student Survival Skills series helps medical students navigate core subjects of the curriculum, providing accessible, short reference guides for OSCE preparation and hospital placements. These guides are the perfect tool for achieving clinical success.

Medical Student Survival Skills: History Taking and Communication Skills is a concise and compact guide to obtaining and recording medical histories and achieving positive patient interactions. The first section explores taking history—from initial introduction to identifying symptoms—and includes abdominal and chest pain, dizziness and vertigo, shortness of breath, sexual history, confusion and loss of memory. Essential patient communication skills and strategies for various situations are described in the second section, including angry patients, instances of drug and alcohol abuse, diabetes counselling and breaking bad news.''',
      link:
          'https://drive.google.com/uc?export=download&id=1lTdZSdpWDhByqp-zuyxPK89o3ius4alG'),
  Book(
      id: 489,
      subject: 'Other Clinical',
      title:
          'The Practical Pocket Guide to History Taking and Clinical Examination',
      writer:
          'David McGowan (Author), Helen Sims (Author), Timothy Williamson (Author), Lesley Thoms (Author), Natalie Smith (Contributor), Charles Zammit (Contributor), Mehar Lad (Contributor), Joseph Norris (Contributor)',
      edition: '1st',
      image:
          'https://images-na.ssl-images-amazon.com/images/I/51taeH9-6IL._SX316_BO1,204,203,200_.jpg',
      rating: 3.9,
      description:
          '''History taking and examination skills are vitally important
in everyday practice. They are examined at all levels of the
undergraduate curriculum and are constantly monitored at
a postgraduate level. To become profi cient in history taking,
key questions should be asked to quickly understand the
exact nature of the illness.

This invaluable guide specifi es the questions required for a
focused history and details the key components of the ideal
examination, resulting in the development of clinical skills
that are timely, comprehensive, relevant and succinct.

Clearly laid out and easy-to-read, The Practical Pocket
Guide to History Taking and Clinical Examination is highly
recommended for medical students and junior doctors
wanting a practical, quick reference to aid confi dence and
develop excellent clinical consultation skills. It is also ideal as
an aide-mémoire for exam preparation.''',
      link:
          'https://drive.google.com/uc?export=download&id=1fEEmlJ9kzeq-AESobGpT6llIJMweafgr'),
];

List<Book> get bookList {
  return books;
}

//Book(
//'Internal Medicine',
//'Harrison ',
//'Author',
//'2nd',
//'images',
//3.9,
//'''    ''',
//''),

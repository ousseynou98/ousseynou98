import SoftwareDeveloper from 'ousseynou';
import { Languages, Frameworks } from 'ousseynou/skills';

class Bio extends SoftwareDeveloper {
  name     = 'Ousseynou DJITE';
  title    = 'Software Developer';
  location = 'Dakar, Senegal';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'TypeScript', 'PHP', ...Languages];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL'];
  frameworks = ['React','Vue','Laravel','Next.js','Nest.js', ...Frameworks];
}

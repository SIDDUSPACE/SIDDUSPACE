import { Card, CardContent } from "@/components/ui/card";
import { FaLinkedin, FaEnvelope, FaGlobe, FaReact, FaPython, FaJava, FaHtml5, FaCss3Alt, FaJsSquare, FaDatabase, FaGithub, FaGitAlt, FaDocker, FaNodeJs, FaCogs, FaMicrochip } from "react-icons/fa";

export default function Portfolio() {
  return (
    <div className="p-8 max-w-5xl mx-auto">
      
      {/* Connect With Me Section */}
      <Card className="mb-8 shadow-lg rounded-2xl">
        <CardContent className="p-6">
          <h2 className="text-2xl font-bold mb-4">Connect with Me</h2>
          <div className="flex gap-6 text-xl">
            <a href="https://www.linkedin.com/in/siddarth-s-079006343/" target="_blank" rel="noopener noreferrer" className="flex items-center gap-2 hover:text-blue-600">
              <FaLinkedin /> LinkedIn
            </a>
            <a href="mailto:siddarth.engineer@gmail.com" className="flex items-center gap-2 hover:text-red-500">
              <FaEnvelope /> Email
            </a>
            <a href="https://siddarth-portfolio.web.app/" target="_blank" rel="noopener noreferrer" className="flex items-center gap-2 hover:text-green-600">
              <FaGlobe /> Portfolio
            </a>
          </div>
        </CardContent>
      </Card>

      {/* Languages & Tools Section */}
      <Card className="shadow-lg rounded-2xl">
        <CardContent className="p-6">
          <h2 className="text-2xl font-bold mb-4">Languages & Tools</h2>
          <div className="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-6 text-4xl">
            
            {/* Programming Languages */}
            <FaPython title="Python" className="hover:text-yellow-500" />
            <FaJava title="Java" className="hover:text-red-500" />
            <FaJsSquare title="JavaScript" className="hover:text-yellow-400" />
            <FaHtml5 title="HTML5" className="hover:text-orange-500" />
            <FaCss3Alt title="CSS3" className="hover:text-blue-500" />
            <FaReact title="React" className="hover:text-cyan-400" />

            {/* Tools & Platforms */}
            <FaGithub title="GitHub" className="hover:text-gray-700" />
            <FaGitAlt title="Git" className="hover:text-orange-600" />
            <FaDocker title="Docker" className="hover:text-blue-600" />
            <FaNodeJs title="Node.js" className="hover:text-green-600" />
            <FaDatabase title="SQL / Databases" className="hover:text-purple-500" />
            <FaCogs title="Embedded Systems" className="hover:text-gray-600" />
            <FaMicrochip title="VLSI & Chip Design" className="hover:text-indigo-600" />

          </div>
        </CardContent>
      </Card>

    </div>
  );
}

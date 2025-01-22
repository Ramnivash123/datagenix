"use client"

import { useState, useEffect } from "react"
import { motion, AnimatePresence } from "framer-motion"
import { Sparkles, HardHatIcon as Hat, Wand2, X } from "lucide-react"
import { Button } from "@/components/ui/button"
import {
  Dialog,
  DialogContent,
  DialogHeader,
  DialogTitle,
  DialogDescription,
  DialogFooter,
} from "@/components/ui/dialog"
import { cn } from "@/lib/utils"

const events = [
  { name: "Data Hunt", description: "Data Hunt intertwines exploration and data analytics, unveiling insights in a unique adventure quest." },
  { name: "Mission Nova", description: "An immersive escape room challenge where participants navigate through a series of data-driven puzzles and challenges, using their analytical skills and teamwork to uncover clues and secure their escape before time runs out." },
  { name: "E-Sports", description: "Valorant - A tactical FPS platform game       Clash Royale - A competitive card-based strategy game" },
  { name: "Anabolic Data", description: "The event showcases data science and fitness, promoting health and community while leveraging analytics for wellness insights." },
]

export default function DataGenix() {
  const [selectedEvent, setSelectedEvent] = useState<string | null>(null)
  const [isSpinning, setIsSpinning] = useState(false)
  const [showEvents, setShowEvents] = useState(false)
  const [isRegistrationOpen, setIsRegistrationOpen] = useState(false)

  const selectRandomEvent = () => {
    setIsSpinning(true)
    setTimeout(() => {
      const randomEvent = events[Math.floor(Math.random() * events.length)]
      setSelectedEvent(randomEvent.name)
      setIsSpinning(false)
    }, 2000)
  }

  const openRegistration = () => {
    setIsRegistrationOpen(true)
  }

  const closeRegistration = () => {
    setIsRegistrationOpen(false)
  }

  const navigateToRegistration = () => {
    // Replace this URL with your actual registration form URL
    window.location.href = "https://docs.google.com/forms/d/e/1FAIpQLSdVhJLVp6sAGznw3jXJYGjGLAYyAFL6YxRQ0gJvRR9BbJAIBA/viewform?usp=header"
  }

  return (
    <div className="min-h-screen bg-gradient-to-br from-blue-600 via-violet-600 to-red-500 px-4 py-8 sm:px-6 lg:px-8">
      <div className="container mx-auto max-w-7xl">
        {/* Title Section */}
        <motion.div
          initial={{ opacity: 0, y: -20 }}
          animate={{ opacity: 1, y: 0 }}
          className="text-center mb-8 sm:mb-12"
        >
          <h1 className="text-4xl sm:text-5xl lg:text-6xl font-bold text-white mb-4 tracking-tight">
            DATAGENIX &apos;25
          </h1>
          <p className="text-lg sm:text-xl text-white/90">Where Data Science Meets Magic</p>
        </motion.div>

        {/* Magical Hat Section */}
        <div className="flex flex-col items-center justify-center gap-6 sm:gap-8 mb-8 sm:mb-12">
          <motion.div
            animate={{ rotate: isSpinning ? 360 : 0 }}
            transition={{ duration: 2, repeat: isSpinning ? Number.POSITIVE_INFINITY : 0 }}
            className="relative"
          >
            <Hat className="w-24 h-24 sm:w-32 sm:h-32 text-white" />
            <motion.div
              animate={{ scale: [1, 1.2, 1] }}
              transition={{ duration: 2, repeat: Number.POSITIVE_INFINITY }}
              className="absolute -inset-4"
            >
              <Sparkles className="w-full h-full text-yellow-300 opacity-75" />
            </motion.div>
          </motion.div>

          <Button
            onClick={selectRandomEvent}
            className="bg-violet-800 hover:bg-violet-700 text-white px-6 py-4 sm:px-8 sm:py-6 text-lg sm:text-xl rounded-full shadow-lg hover:shadow-xl transform hover:scale-105 transition-all"
          >
            <Wand2 className="mr-2 h-5 w-5 sm:h-6 sm:w-6" />
            Oh Great Hat! You tell me!
          </Button>
        </div>

        {/* Selected Event Display */}
        <AnimatePresence>
          {selectedEvent && (
            <motion.div
              initial={{ opacity: 0, y: 20 }}
              animate={{ opacity: 1, y: 0 }}
              exit={{ opacity: 0 }}
              className="text-center mb-8 sm:mb-12"
            >
              <div className="bg-white/10 backdrop-blur-md rounded-lg p-4 sm:p-6 max-w-md mx-auto">
                <h2 className="text-xl sm:text-2xl font-bold text-white mb-3 sm:mb-4">The Hat Has Chosen:</h2>
                <p className="text-2xl sm:text-3xl font-bold text-yellow-300 mb-3 sm:mb-4">{selectedEvent}</p>
                <p className="text-sm sm:text-base text-white/90 italic">
                  "But remember, young wizard, this is merely a suggestion. The true power lies in your own choice!"
                </p>
              </div>
            </motion.div>
          )}
        </AnimatePresence>

        {/* Show All Events Button */}
        <div className="text-center mb-6 sm:mb-8">
          <Button
            onClick={() => setShowEvents(!showEvents)}
            variant="outline"
            className="text-white border-white hover:bg-white/10"
          >
            {showEvents ? "Hide Events" : "Show All Events"}
          </Button>
        </div>

        {/* Events Grid */}
        <AnimatePresence>
          {showEvents && (
            <motion.div
              initial={{ opacity: 0 }}
              animate={{ opacity: 1 }}
              exit={{ opacity: 0 }}
              className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 mb-8 sm:mb-12"
            >
              {events.map((event, index) => (
                <motion.div
                  key={event.name}
                  initial={{ opacity: 0, y: 20 }}
                  animate={{ opacity: 1, y: 0 }}
                  transition={{ delay: index * 0.1 }}
                  className="bg-white/10 backdrop-blur-md rounded-lg p-4 sm:p-6 hover:bg-white/20 transition-all cursor-pointer"
                >
                  <h3 className="text-lg sm:text-xl font-bold text-white mb-2">{event.name}</h3>
                  <p className="text-sm sm:text-base text-white/80">{event.description}</p>
                </motion.div>
              ))}
            </motion.div>
          )}
        </AnimatePresence>

        {/* Registration Button */}
        <div className="text-center">
          <Button
            onClick={openRegistration}
            className="bg-gradient-to-r from-violet-600 to-red-500 text-white px-6 py-3 sm:px-8 sm:py-4 rounded-full text-lg sm:text-xl font-bold shadow-lg hover:shadow-xl transform hover:scale-105 transition-all"
          >
            Register Now for DataGenix &apos;25
          </Button>
        </div>

        {/* Registration Dialog */}
        <Dialog open={isRegistrationOpen} onOpenChange={setIsRegistrationOpen}>
          <DialogContent className="sm:max-w-[425px]">
            <DialogHeader>
              <DialogTitle>Register for DataGenix &apos;25</DialogTitle>
              <DialogDescription>Are you ready to embark on a magical data science journey?</DialogDescription>
            </DialogHeader>
            <DialogFooter>
              <Button variant="outline" onClick={closeRegistration}>
                Cancel
              </Button>
              <Button onClick={navigateToRegistration}>Go to Registration Form</Button>
            </DialogFooter>
          </DialogContent>
        </Dialog>
      </div>
    </div>
  )
}


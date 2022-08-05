# React Masterclass

Learn and dominate the React ecosystem once and for all.

##### UPDATE 22-08-03 POWER README ######


const boxVariants = {
  initial: {
    opacity:0,
    scale: 0
  },
  visible: {
    opacity:1,
    scale: 1,
    rotateZ: 360,
  },
  leaving: {
    opacity:0,
    scale: 0,
    y: 20,
  }
}
<AnimatePresence>{showing ? <Box   variants={boxVariants} initial="initial" animate="visible" exit="leaving"/> : null}</AnimatePresence> 
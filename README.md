# Poisson Image Editing 
This project implements techniques detailed in the paper Poisson image editing by Patrick Pérez, Michel Gangnet, and Andrew Blake.
https://dl.acm.org/doi/pdf/10.1145/882262.882269

The implementation includes:

- Discrete Poisson solver
- Seamless cloning by importing gradients
- Seamless cloning by mixing gradients
- Local color changes

## Libraries
- cv2 (image load, resize)
- numpy
- scipy (linear algebra)
- matplotlib (plot, polygon region selector)
  
## Implementations
### Region Filling
<img width="717" alt="Screenshot 2025-01-01 at 16 06 36" src="https://github.com/user-attachments/assets/1df7896f-5df0-4d24-a506-816013a0b471" />

### Seamless Cloning 
#### Importing gradients
<img width="756" alt="Screenshot 2025-01-01 at 16 06 58" src="https://github.com/user-attachments/assets/c29e675a-0092-4438-8c41-129a83ece0fd" />

#### Mixing gradients
<img width="761" alt="Screenshot 2025-01-01 at 16 07 19" src="https://github.com/user-attachments/assets/8898503d-1512-4e09-998e-2b5e1721620d" />

#### Importing gradients vs. Mixing gradients
<img width="696" alt="Screenshot 2025-01-01 at 16 07 46" src="https://github.com/user-attachments/assets/7e313e75-e3bd-4a87-b714-4232e5bf9e9a" />
<img width="730" alt="Screenshot 2025-01-01 at 16 09 31" src="https://github.com/user-attachments/assets/6331d490-5187-4824-b29e-a259c519b4cd" />

### Colored Images 
<img width="710" alt="Screenshot 2025-01-01 at 16 08 26" src="https://github.com/user-attachments/assets/717c6ef4-a7d8-47c4-848b-ee8d8c8740ca" />
<img width="727" alt="Screenshot 2025-01-01 at 16 08 36" src="https://github.com/user-attachments/assets/206cf0ad-4454-4537-b622-d19fd8b36281" />

### Local Color Changes
<img width="847" alt="Screenshot 2025-01-01 at 16 09 51" src="https://github.com/user-attachments/assets/a0c155ea-463a-4615-90f6-c6659df8f771" />







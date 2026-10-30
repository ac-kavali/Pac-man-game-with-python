import pygame
import sys

pygame.init()

WIDTH = 800
HEIGHT = 600
FPS = 60

screen = pygame.display.set_mode((WIDTH, HEIGHT))
pygame.display.set_caption("Pac-Man")

clock = pygame.time.Clock()

running = True

while running:

    # 1. HANDLE EVENTS
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            running = False

        if event.type == pygame.KEYDOWN:
            if event.key == pygame.K_ESCAPE:
                running = False

    # 2. UPDATE GAME LOGIC
    # update_game()

    # 3. RENDER GRAPHICS
    screen.fill((0, 0, 0))

    # draw_maze()
    # draw_pacman()
    # draw_ghosts()
    # draw_score()

    pygame.display.flip()

    # 4. CONTROL FPS
    clock.tick(FPS)

pygame.quit()
sys.exit()

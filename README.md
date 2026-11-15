// Passo 3: ligar o forno
printf("\nPasso 3: Ligando o forno a 180 graus...\n");

// Passo 4: misturar (for)
printf("Passo 4: Misturando a massa\n");
for (int i = 1; i <= 5; i++) {
    printf("  Mexendo... volta %d\n", i);
}

// Passo 5: assar (while)
printf("Passo 5: Colocando no forno\n");
while (tempo_forno < 40) {
    tempo_forno = tempo_forno + 10;
    printf("  Assando... %d minutos\n", tempo_forno);
}

// Passo 6: finalizar
printf("\nPasso 6: Tirar do forno e esperar esfriar\n");
printf("Bolo pronto! Bom apetite!\n");

return 0;
}

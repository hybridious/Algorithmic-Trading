CC=g++
CFLAGS=-c -std=c++11
O=main.o MomentumStrategy.o Strategy.o TradeDay.o StrategyResult.o Logger.o MomentumStrategyData.o Params.o CSVReader.o UnitTester.o CSVWriter.o MutantFrogStrategy.o TradingInfluences.o

all: AlgorithmicTrading

AlgorithmicTrading: $(O)
	$(CC) $(O) -o AlgorithmicTrading

main.o: main.cpp
	$(CC) $(CFLAGS) main.cpp

MomentumStrategy.o: MomentumStrategy.cpp
	$(CC) $(CFLAGS) MomentumStrategy.cpp

Strategy.o: Strategy.cpp
	$(CC) $(CFLAGS) Strategy.cpp

TradeDay.o: TradeDay.cpp
	$(CC) $(CFLAGS) TradeDay.cpp

StrategyResult.o: StrategyResult.cpp
	$(CC) $(CFLAGS) StrategyResult.cpp

Logger.o: Logger.cpp
	$(CC) $(CFLAGS) Logger.cpp

MomentumStrategyData.o: MomentumStrategyData.cpp
	$(CC) $(CFLAGS) MomentumStrategyData.cpp

Params.o: Params.cpp
	$(CC) $(CFLAGS) Params.cpp

CSVReader.o: CSVReader.cpp
	$(CC) $(CFLAGS) CSVReader.cpp

UnitTester.o: UnitTester.cpp
	$(CC) $(CFLAGS) UnitTester.cpp

CSVWriter.o: CSVWriter.cpp
	$(CC) $(CFLAGS) CSVWriter.cpp

CSVWriter.o: CSVWriter.cpp
	$(CC) $(CFLAGS) CSVWriter.cpp

MutantFrogStrategy.o: MutantFrogStrategy.cpp
	$(CC) $(CFLAGS) MutantFrogStrategy.cpp

TradingInfluences.o: TradingInfluences.cpp
	$(CC) $(CFLAGS) TradingInfluences.cpp
	
clean:
	rm *.o AlgorithmicTrading *.log *.csv
